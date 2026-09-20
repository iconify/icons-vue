<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3g_wrr7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3g_wrr7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-l-circle" /></template>
