<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p209yfbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p209yfbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-wifi-line" /></template>
