<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux4ezo1do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux4ezo1do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:info-box-sharp" /></template>
