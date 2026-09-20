<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woa1r2bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woa1r2bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-arrow-right" /></template>
