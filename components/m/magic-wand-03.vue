<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xxftuhv7v.css';
import '../../css/i/iv91gxb2w.css';
import '../../css/t/t9behylkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xxftuhv7v"/><path class="iv91gxb2w"/><path class="t9behylkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magic-wand-03" /></template>
