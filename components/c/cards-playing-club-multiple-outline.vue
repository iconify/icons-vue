<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdlrif8_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdlrif8_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-club-multiple-outline" /></template>
