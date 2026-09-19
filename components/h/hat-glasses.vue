<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tr7sirbvc.css';
import '../../css/e/ej5a_l4in.css';
import '../../css/k/kgtb4abpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tr7sirbvc"/><path class="ej5a_l4in"/><path class="kgtb4abpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hat-glasses" /></template>
