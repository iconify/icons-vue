<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u0ck9yb3g.css';
import '../../css/u/un29iqbuk.css';
import '../../css/f/fuprorb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u0ck9yb3g"/><path class="un29iqbuk"/><path class="fuprorb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-broken" /></template>
