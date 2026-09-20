<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s35955b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s35955b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gps-2-sharp" /></template>
