<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fq1xjqp5f.css';
import '../../css/k/kmb_csbur.css';
import '../../css/v/vyfqjvtfg.css';
import '../../css/i/inpq1w8bk.css';
import '../../css/o/oi1g4_sbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fq1xjqp5f wm-deco"/><path class="kmb_csbur wm-deco"/><path class="vyfqjvtfg wm-k"/><path class="inpq1w8bk wm-a"/><path class="oi1g4_sbp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:edit-blueprint" /></template>
