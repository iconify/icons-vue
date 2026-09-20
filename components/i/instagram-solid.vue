<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnh_3dhgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnh_3dhgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:instagram-solid" /></template>
