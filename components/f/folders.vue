<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="4.75 2.25 4.75 10.25 14.25 10.25 14.25 3.75 9.25 3.75 7.75 2.25"/><polyline points="4.75 5.25 1.75 5.25 1.75 13.25 11.25 13.25 11.25 10.25"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:folders" /></template>
