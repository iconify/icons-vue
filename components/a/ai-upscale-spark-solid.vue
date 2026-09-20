<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te3uvd3yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te3uvd3yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-upscale-spark-solid" /></template>
