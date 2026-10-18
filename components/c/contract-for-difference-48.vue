<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_z99bhx.css';
import '../../css/w/w3ql33bwg.css';
import '../../css/w/wm3m0vl4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="w3ql33bwg"/><path class="wm3m0vl4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-for-difference-48" /></template>
