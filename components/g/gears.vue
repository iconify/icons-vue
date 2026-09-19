<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy-g98bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gy-g98bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gears" /></template>
