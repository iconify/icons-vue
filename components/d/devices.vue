<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzeb2oyjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzeb2oyjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:devices" /></template>
