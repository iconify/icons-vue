<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlsi6_kti.css';
import '../../css/n/njlpr9bmf.css';
import '../../css/e/e-s8zybio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlsi6_kti"/><path class="njlpr9bmf"/><path class="e-s8zybio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-points-light" /></template>
