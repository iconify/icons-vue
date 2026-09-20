<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgbh2sbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rgbh2sbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-and-arrow-right-above-arrow-left" /></template>
