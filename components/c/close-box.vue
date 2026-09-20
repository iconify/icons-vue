<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czkxmpq8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czkxmpq8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:close-box" /></template>
