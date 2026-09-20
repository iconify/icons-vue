<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdl857bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdl857bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:checks-line" /></template>
