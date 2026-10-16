<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_qrf6bex.css';
import '../../css/b/bwg811bpd.css';
import '../../css/o/orqjejdjp.css';
import '../../css/v/vlrk2yboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_qrf6bex"/><path class="bwg811bpd"/><path class="orqjejdjp"/><path class="vlrk2yboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-cell-48-bold" /></template>
