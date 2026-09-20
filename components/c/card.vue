<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu204obny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu204obny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card" /></template>
