<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzpjhuv5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzpjhuv5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:draw-ellipse-segment" /></template>
