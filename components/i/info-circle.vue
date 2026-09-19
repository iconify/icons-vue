<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aqsexabqu.css';
import '../../css/v/v6zwtfsnc.css';
import '../../css/w/wqaq_tblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="aqsexabqu"/><circle class="v6zwtfsnc"/><path clip-rule="evenodd" class="wqaq_tblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:info-circle" /></template>
