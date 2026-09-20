<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/firyb22yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="firyb22yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-bar-right" /></template>
