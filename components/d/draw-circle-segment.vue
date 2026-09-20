<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdvoe2bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdvoe2bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:draw-circle-segment" /></template>
