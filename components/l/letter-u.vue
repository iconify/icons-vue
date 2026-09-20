<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my8u2_bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my8u2_bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-u" /></template>
