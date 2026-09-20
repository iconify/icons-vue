<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryc_9ybce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryc_9ybce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:file-multiple" /></template>
