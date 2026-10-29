<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dp04q_i-b.css';
import '../../css/a/atb3k23ro.css';
import '../../css/f/fwuicyddt.css';
import '../../css/u/u-tk08bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dp04q_i-b"/><path class="atb3k23ro wm-a"/><path class="fwuicyddt wm-k"/><path class="u-tk08bep wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:choco-strawberry-sketch" /></template>
