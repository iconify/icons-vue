<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n58ssxigb.css';
import '../../css/l/lt7j86jjt.css';
import '../../css/t/tw2p-vbaq.css';
import '../../css/l/l6md27rub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n58ssxigb"/><path class="lt7j86jjt"/><path class="tw2p-vbaq"/><path class="l6md27rub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-broken" /></template>
