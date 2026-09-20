<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy0b-_gxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy0b-_gxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-aspect-ratio" /></template>
