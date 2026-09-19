<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekoozwbhq.css';
import '../../css/c/csilaps2y.css';
import '../../css/n/nz2-r9bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ekoozwbhq"/><rect class="csilaps2y"/><path class="nz2-r9bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hardware-chip-outline" /></template>
