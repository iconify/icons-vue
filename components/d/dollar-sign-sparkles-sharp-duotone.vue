<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/qtwle9b1d.css';
import '../../css/s/snibgdcaa.css';
import '../../css/t/tphcq3b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qtwle9b1d"/><path class="snibgdcaa"/><path class="tphcq3b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dollar-sign-sparkles-sharp-duotone" /></template>
