<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cx4bwonyh.css';
import '../../css/n/n4g3xacqe.css';
import '../../css/k/kz8vnnv1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="cx4bwonyh"/><path class="n4g3xacqe wm-a"/><path class="kz8vnnv1h wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-plus-solid" /></template>
