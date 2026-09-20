<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr2fe1bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2fe1bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cpu-sharp" /></template>
