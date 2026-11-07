<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l1cob4bep.css';
import '../../css/w/wqs3cnbmu.css';
import '../../css/i/iscitzuxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l1cob4bep"/><path class="wqs3cnbmu"/><path class="iscitzuxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-minimalistic-line-duotone" /></template>
