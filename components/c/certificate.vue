<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m7n95beto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="11.25 1.75 2.75 1.75 2.75 13.25 5.25 13.25"/><polyline points="8.75 9.75 8.25 14.25 10.5 13.25 12.75 14.25 12.25 9.75"/><circle class="m7n95beto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:certificate" /></template>
