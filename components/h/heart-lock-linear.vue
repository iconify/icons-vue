<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/un29iqbuk.css';
import '../../css/f/fuprorb1g.css';
import '../../css/q/qjcn1b-9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="un29iqbuk"/><path class="fuprorb1g"/><path class="qjcn1b-9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-linear" /></template>
