<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6p6i_bqp.css';
import '../../css/n/n-w6_w_ot.css';
import '../../css/t/to4xcybuh.css';
import '../../css/q/qxvivc_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u6p6i_bqp"/><path class="n-w6_w_ot"/><path class="to4xcybuh"/><path class="qxvivc_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charge-card-48" /></template>
