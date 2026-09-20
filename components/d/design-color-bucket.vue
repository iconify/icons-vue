<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_4157bgu.css';
import '../../css/f/frw4m7ekt.css';
import '../../css/e/ehesr7bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_4157bgu"/><path class="frw4m7ekt"/><path class="ehesr7bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-color-bucket" /></template>
