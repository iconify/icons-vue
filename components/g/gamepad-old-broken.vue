<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fvkw4oiyc.css';
import '../../css/v/v5l5vgbks.css';
import '../../css/k/knx1hwb4l.css';
import '../../css/e/e_un4ubpg.css';
import '../../css/x/xkvin1h0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvkw4oiyc"/><path class="v5l5vgbks"/><path class="knx1hwb4l"/><path class="e_un4ubpg"/><path class="xkvin1h0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-old-broken" /></template>
