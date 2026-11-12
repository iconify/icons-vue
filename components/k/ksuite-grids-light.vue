<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlsi6_kti.css';
import '../../css/n/njlpr9bmf.css';
import '../../css/q/qbc0ipycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlsi6_kti"/><path class="njlpr9bmf"/><path class="qbc0ipycg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-grids-light" /></template>
