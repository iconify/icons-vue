<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j-v4rgbdl.css';
import '../../css/u/u00ey8bps.css';
import '../../css/d/dmfni0bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j-v4rgbdl"/><circle class="u00ey8bps"/><path class="dmfni0bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-unread-linear" /></template>
