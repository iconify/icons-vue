<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muem-vb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muem-vb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-front-variant" /></template>
