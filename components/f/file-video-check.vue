<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7trzwh8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7trzwh8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-video-check" /></template>
