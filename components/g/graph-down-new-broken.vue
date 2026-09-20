<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ley58n3yy.css';
import '../../css/u/u00ey8bps.css';
import '../../css/a/ab62pjuns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ley58n3yy"/><circle class="u00ey8bps"/><path class="ab62pjuns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-down-new-broken" /></template>
