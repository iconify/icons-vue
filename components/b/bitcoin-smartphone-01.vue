<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bs2p8bb3r.css';
import '../../css/w/watrmtrxt.css';
import '../../css/t/td99tubxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bs2p8bb3r"/><path class="watrmtrxt"/><path class="td99tubxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-smartphone-01" /></template>
