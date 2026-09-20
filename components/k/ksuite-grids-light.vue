<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og_f3_bmu.css';
import '../../css/w/waab1-svo.css';
import '../../css/q/qbc0ipycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og_f3_bmu"/><path class="waab1-svo"/><path class="qbc0ipycg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-grids-light" /></template>
