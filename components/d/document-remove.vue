<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/ftnnt4b-s.css';
import '../../css/i/iwk_ym9zp.css';
import '../../css/t/tuv9vbcyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ftnnt4b-s"/><path class="iwk_ym9zp"/><path class="tuv9vbcyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:document-remove" /></template>
