<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_z99bhx.css';
import '../../css/g/gzw4njbqf.css';
import '../../css/t/t_h9pt-ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="gzw4njbqf"/><path class="t_h9pt-ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:budget-48" /></template>
