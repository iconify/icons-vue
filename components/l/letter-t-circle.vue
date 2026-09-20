<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1x3n41vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1x3n41vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-t-circle" /></template>
