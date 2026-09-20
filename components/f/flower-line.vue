<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-eg3fbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-eg3fbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flower-line" /></template>
