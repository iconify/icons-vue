<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoel_3brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoel_3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:apple-solid" /></template>
