<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lm2y_hbzh.css';
import '../../css/k/kiph3vb6t.css';
import '../../css/x/x40pc3c5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="lm2y_hbzh"/><path class="kiph3vb6t"/><path class="x40pc3c5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-chart-notification" /></template>
