<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lsdx72hdd.css';
import '../../css/p/po7_ugb8x.css';
import '../../css/e/ehvyd8b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lsdx72hdd"/><path class="po7_ugb8x"/><path class="ehvyd8b2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:boxer" /></template>
