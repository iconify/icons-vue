<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iq5e1h6ad.css';
import '../../css/d/ds7dl9bhv.css';
import '../../css/m/m5m3ywbwl.css';
import '../../css/t/turu6r4ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iq5e1h6ad"/><path class="ds7dl9bhv"/><path class="m5m3ywbwl"/><path class="turu6r4ex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:headstone" /></template>
