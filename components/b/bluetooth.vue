<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1blm2b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1blm2b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bluetooth" /></template>
