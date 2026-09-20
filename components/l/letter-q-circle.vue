<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs5sg8uyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs5sg8uyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-q-circle" /></template>
