<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc-gqt2en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-gqt2en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-justify-start-sharp" /></template>
