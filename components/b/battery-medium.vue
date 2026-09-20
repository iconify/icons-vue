<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc2qde7lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2qde7lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:battery-medium" /></template>
