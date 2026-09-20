<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htij__bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htij__bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bell-ring-sharp" /></template>
