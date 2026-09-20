<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry8x41zgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry8x41zgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-minus" /></template>
