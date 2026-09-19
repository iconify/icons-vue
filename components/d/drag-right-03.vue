<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hrt15xihn.css';
import '../../css/d/dfb6i3blf.css';
import '../../css/s/shnvllc_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hrt15xihn"/><path class="dfb6i3blf"/><path class="shnvllc_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-right-03" /></template>
