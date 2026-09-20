<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcq9aufca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcq9aufca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:door-closed-sharp" /></template>
