<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l9_wagkcs.css';
import '../../css/w/wzd_ul5ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l9_wagkcs"/><path clip-rule="evenodd" class="wzd_ul5ss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-diaphragm-outline-24px" /></template>
