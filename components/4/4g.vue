<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp-kso11r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp-kso11r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:4g" /></template>
