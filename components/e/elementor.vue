<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mobnpr2vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mobnpr2vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:elementor" /></template>
