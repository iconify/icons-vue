<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjwczuzkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjwczuzkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-sharp" /></template>
