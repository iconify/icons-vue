<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hl0mleb2v.css';
import '../../css/n/n8st7-4by.css';
import '../../css/x/x_2xbjk-i.css';
import '../../css/m/msronwbal.css';
import '../../css/o/o95ej6b5s.css';
import '../../css/b/bh5981mts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hl0mleb2v"/><path class="n8st7-4by"/><path class="x_2xbjk-i"/><path class="msronwbal"/><path class="o95ej6b5s"/><path class="bh5981mts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-2-linear" /></template>
