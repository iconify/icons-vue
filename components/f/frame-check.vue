<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw19l9bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw19l9bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:frame-check" /></template>
