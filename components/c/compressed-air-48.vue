<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmy2czeki.css';
import '../../css/o/oo8c23mgb.css';
import '../../css/w/w94q1qbjf.css';
import '../../css/k/kto--z_xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmy2czeki"/><path class="oo8c23mgb"/><path class="w94q1qbjf"/><path class="kto--z_xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressed-air-48" /></template>
