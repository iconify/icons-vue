<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpger37ta.css';
import '../../css/o/od_zyybil.css';
import '../../css/l/lmps3mg_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpger37ta"/><path class="od_zyybil"/><path class="lmps3mg_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:butterfly-48" /></template>
