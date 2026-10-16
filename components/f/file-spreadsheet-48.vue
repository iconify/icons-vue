<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezwopb-j.css';
import '../../css/i/im6_9vhgw.css';
import '../../css/r/rfgrjcbjr.css';
import '../../css/q/qel2yy7gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="im6_9vhgw"/><path class="rfgrjcbjr"/><path class="qel2yy7gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-spreadsheet-48" /></template>
