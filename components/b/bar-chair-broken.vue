<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/klxj4gb1b.css';
import '../../css/r/rw1sm-ddm.css';
import '../../css/i/i-l_6qbww.css';
import '../../css/a/awb7-ex2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="klxj4gb1b"/><path class="rw1sm-ddm"/><path class="i-l_6qbww"/><path class="awb7-ex2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bar-chair-broken" /></template>
