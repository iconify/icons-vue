<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr17nbd6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr17nbd6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:drum" /></template>
