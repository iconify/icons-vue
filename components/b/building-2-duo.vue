<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/drgourb2x.css';
import '../../css/e/ee72xe_hx.css';
import '../../css/b/bt4eanb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="drgourb2x"/><path class="ee72xe_hx wm-a"/><path class="bt4eanb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-2-duo" /></template>
