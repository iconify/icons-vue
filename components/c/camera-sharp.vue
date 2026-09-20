<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppplzd1pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppplzd1pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:camera-sharp" /></template>
