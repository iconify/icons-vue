<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvvss987d.css';
import '../../css/p/p5oy8duvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gvvss987d"/><path class="p5oy8duvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-bin" /></template>
