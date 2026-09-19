<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3zs83btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y3zs83btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud-cloud" /></template>
