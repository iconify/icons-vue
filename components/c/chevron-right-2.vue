<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0xv2tbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xv2tbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-right-2" /></template>
