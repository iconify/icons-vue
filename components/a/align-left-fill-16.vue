<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv97p5bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fv97p5bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-left-fill-16" /></template>
