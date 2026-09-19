<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="2.75 2.75 2.75 13.25 13.25 13.25 13.25 5.75 10.25 2.75"/><polyline points="5.75 13.25 5.75 9.75 10.25 9.75 10.25 13.25"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:floppy-disk" /></template>
