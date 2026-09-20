<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiir8lb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiir8lb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:alarm-clock" /></template>
