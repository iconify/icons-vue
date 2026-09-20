<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s8bb_db3f.css';
import '../../css/m/mfzpinb3h.css';
import '../../css/r/rlh6hbbsu.css';
import '../../css/p/p2y-_pb4l.css';
import '../../css/a/a9z4j2bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="s8bb_db3f"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.7s" dur="0.5s" values="0;64"/></rect><path class="mfzpinb3h"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.5s" dur="0.2s" values="0;6"/></path><path class="rlh6hbbsu"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.2s" dur="0.2s" values="0;12"/></path><path class="p2y-_pb4l"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.2s" values="0;9"/></path></g><rect height="3" class="a9z4j2bgh"><animate fill="freeze" attributeName="height" begin="0.5s" dur="0.2s" values="3;0"/></rect>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:calendar-out" /></template>
