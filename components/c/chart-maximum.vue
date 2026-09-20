<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07tmccvv.css';
import '../../css/d/d4oe1undt.css';
import '../../css/p/pim_cdbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="d4oe1undt"/><path class="pim_cdbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-maximum" /></template>
