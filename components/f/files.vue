<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="9.25 1.75 13.25 5.75 13.25 11.25 5.75 11.25 5.75 1.75"/><polyline points="9.25 2.25 9.25 5.75 12.75 5.75"/><polyline points="10.25 11.75 10.25 14.25 2.75 14.25 2.75 4.75 5.25 4.75"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:files" /></template>
