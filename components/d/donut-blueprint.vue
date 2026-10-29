<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/db9oi35bt.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/b/bk5sigzvt.css';
import '../../css/e/exdxo5cyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="db9oi35bt wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="bk5sigzvt wm-k"/><path class="exdxo5cyc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:donut-blueprint" /></template>
