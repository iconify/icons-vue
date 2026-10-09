<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqlp_3l8j.css';
import '../../css/x/xajndacdt.css';
import '../../css/t/tco_xthkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqlp_3l8j"/><path class="xajndacdt"/><path class="tco_xthkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:log-out-48" /></template>
