<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/th_2vrbuv.css';
import '../../css/o/oorbizavx.css';
import '../../css/g/ghv12qbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th_2vrbuv"/><path class="oorbizavx"/><path class="ghv12qbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-left-right-ellipsis-linear" /></template>
