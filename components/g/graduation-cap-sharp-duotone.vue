<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/k9_6zp9ba.css';
import '../../css/i/i2p_dkbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k9_6zp9ba"/><path clip-rule="evenodd" class="i2p_dkbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:graduation-cap-sharp-duotone" /></template>
