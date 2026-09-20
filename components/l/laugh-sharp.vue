<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyxjm0p6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyxjm0p6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:laugh-sharp" /></template>
