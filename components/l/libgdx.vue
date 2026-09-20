<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc9zr_r5s.css';
import '../../css/d/d3xjujk0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nc9zr_r5s"/><path class="d3xjujk0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:libgdx" /></template>
