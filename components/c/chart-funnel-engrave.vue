<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/glpyvrt8s.css';
import '../../css/g/gqtz-uhbr.css';
import '../../css/d/dakzdk03i.css';
import '../../css/f/flbsvpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="glpyvrt8s wm-k"/><path class="gqtz-uhbr wm-shadow"/><path class="dakzdk03i wm-k"/><path class="flbsvpbyj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-engrave" /></template>
