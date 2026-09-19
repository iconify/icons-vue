<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nki8t3b7j.css';
import '../../css/q/qhdy6vbit.css';
import '../../css/m/m5luvtbuz.css';
import '../../css/t/tgrin9b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nki8t3b7j"/><path class="qhdy6vbit"/><path class="m5luvtbuz"/><path class="tgrin9b-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:graph-death-rate-decreasing" /></template>
