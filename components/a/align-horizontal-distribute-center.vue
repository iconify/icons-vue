<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd3phbbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd3phbbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-distribute-center" /></template>
