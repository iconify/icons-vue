<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub5-3ubuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub5-3ubuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-pdfbox" /></template>
