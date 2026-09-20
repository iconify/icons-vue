<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1t-eearw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1t-eearw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:building-sharp" /></template>
