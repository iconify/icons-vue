<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4f6_pbnc.css';
import '../../css/t/tolo0jbro.css';
import '../../css/z/zh_bxpbcd.css';
import '../../css/n/nyl_ck5xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h4f6_pbnc"/><path class="tolo0jbro"/><path class="zh_bxpbcd"/><path class="nyl_ck5xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:data-centre-48" /></template>
