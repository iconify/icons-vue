<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itv0f-bax.css';
import '../../css/n/ncx05ab2q.css';
import '../../css/t/tthe00koa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itv0f-bax"/><path class="ncx05ab2q"/><path class="tthe00koa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:import-export-20-bold" /></template>
