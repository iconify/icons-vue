<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm4isn3js.css';
import '../../css/y/y711oejcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gm4isn3js"/><path class="y711oejcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-ceiling" /></template>
