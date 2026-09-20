<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cly2z6b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cly2z6b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:device-vibrate" /></template>
