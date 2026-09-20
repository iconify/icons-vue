<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viv1grb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viv1grb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-pdf" /></template>
