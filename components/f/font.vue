<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccq_gd3ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ccq_gd3ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:font" /></template>
