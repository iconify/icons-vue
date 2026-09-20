<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd8y_juzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd8y_juzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:flip-to-front" /></template>
