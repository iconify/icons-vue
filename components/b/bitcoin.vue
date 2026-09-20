<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k61-bn06g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k61-bn06g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bitcoin" /></template>
