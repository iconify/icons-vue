<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsv-5w5ym.css';
import '../../css/v/vfhoccbdf.css';
import '../../css/v/vwz4-ew1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hsv-5w5ym"/><path class="vfhoccbdf"/><path class="vwz4-ew1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:building-real-eastate-sign-house-2" /></template>
