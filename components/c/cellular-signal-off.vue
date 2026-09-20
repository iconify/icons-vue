<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8cde-bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8cde-bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cellular-signal-off" /></template>
