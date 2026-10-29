<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/plgmnm5bs.css';
import '../../css/r/rvadobhgc.css';
import '../../css/c/c-n-9gpof.css';
import '../../css/k/km9xt0bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="plgmnm5bs wm-k"/><path class="rvadobhgc wm-shadow"/><path class="c-n-9gpof wm-k"/><path class="km9xt0bvl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-drive-engrave" /></template>
