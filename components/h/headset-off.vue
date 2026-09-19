<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aqx1n_x7l.css';
import '../../css/l/lbt39w0vi.css';
import '../../css/r/rth5aubws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aqx1n_x7l"/><path class="lbt39w0vi"/><path class="rth5aubws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:headset-off" /></template>
