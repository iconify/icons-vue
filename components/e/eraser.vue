<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_tqlb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rv_tqlb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:eraser" /></template>
