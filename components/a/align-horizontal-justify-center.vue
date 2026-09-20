<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5f73wbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5f73wbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-justify-center" /></template>
