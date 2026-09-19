<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7vjo-dfp.css';
import '../../css/p/pb1v7pbfq.css';
import '../../css/m/moke7fbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7vjo-dfp"/><path class="pb1v7pbfq"/><path class="moke7fbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:loop-1" /></template>
