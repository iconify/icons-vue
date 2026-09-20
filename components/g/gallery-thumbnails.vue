<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-f8mxb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-f8mxb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gallery-thumbnails" /></template>
