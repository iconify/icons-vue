<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvmh4mb4l.css';
import '../../css/s/s0fmfdclg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mvmh4mb4l"/><path class="s0fmfdclg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-price-20" /></template>
