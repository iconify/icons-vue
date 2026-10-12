<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d_2a_sbsk.css';
import '../../css/m/mgc_dm9_h.css';
import '../../css/s/s805e4aqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d_2a_sbsk"/><path class="mgc_dm9_h"/><path class="s805e4aqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ad-duotone" /></template>
