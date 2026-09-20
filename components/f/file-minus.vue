<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgaw-li2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgaw-li2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:file-minus" /></template>
