<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt-98jkjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-98jkjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cctv-off-line" /></template>
