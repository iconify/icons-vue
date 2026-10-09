<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lscp_lbsk.css';
import '../../css/e/euqlsybkd.css';
import '../../css/t/tliwn4baj.css';
import '../../css/y/yxnumh36j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lscp_lbsk"/><path class="euqlsybkd"/><path class="tliwn4baj"/><path class="yxnumh36j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-flow-48" /></template>
