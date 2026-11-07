<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ojv2i-bxi.css';
import '../../css/z/zv_roib3z.css';
import '../../css/h/hg3jlpbvn.css';
import '../../css/l/lt87iveio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ojv2i-bxi"/><path class="zv_roib3z"/><path class="hg3jlpbvn"/><path class="lt87iveio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-linear" /></template>
