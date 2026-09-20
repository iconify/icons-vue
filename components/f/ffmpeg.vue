<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0612-4uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0612-4uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ffmpeg" /></template>
