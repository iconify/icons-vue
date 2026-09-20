<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut8x6ebqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut8x6ebqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:linux" /></template>
