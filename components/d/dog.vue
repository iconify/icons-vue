<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_61xr4wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j_61xr4wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dog" /></template>
