<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muzy8absx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muzy8absx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-code" /></template>
