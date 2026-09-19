<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lxeer2b8m.css';
import '../../css/v/v7punz0qn.css';
import '../../css/f/fh38--b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxeer2b8m"/><path class="v7punz0qn"/><path class="fh38--b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chemistry-03" /></template>
