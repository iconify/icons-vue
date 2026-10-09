<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl_b26bzx.css';
import '../../css/o/oewx-qbfa.css';
import '../../css/m/mzed39b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rl_b26bzx"/><path class="oewx-qbfa"/><path class="mzed39b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fingerprint-48-bold" /></template>
