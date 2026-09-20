<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6_e-hbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6_e-hbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-open-sharp" /></template>
