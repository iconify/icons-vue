<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fic-uk24y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fic-uk24y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout" /></template>
