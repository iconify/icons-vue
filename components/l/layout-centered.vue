<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkm56n7je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jkm56n7je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-centered" /></template>
