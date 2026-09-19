<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/frli32bnn.css';
import '../../css/l/ljd34hyaq.css';
import '../../css/p/p2wr0qbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="frli32bnn"/><path class="ljd34hyaq"/><path class="p2wr0qbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:location-10" /></template>
