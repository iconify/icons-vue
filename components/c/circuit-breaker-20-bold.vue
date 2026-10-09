<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzpjlsbtf.css';
import '../../css/g/gksydibqx.css';
import '../../css/q/qpu6gyb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yzpjlsbtf"/><path class="gksydibqx"/><path class="qpu6gyb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circuit-breaker-20-bold" /></template>
