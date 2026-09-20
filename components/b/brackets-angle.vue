<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t00jw3bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t00jw3bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-angle" /></template>
