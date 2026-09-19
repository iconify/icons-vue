<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg7w6acib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sg7w6acib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:eye" /></template>
