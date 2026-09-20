<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/raphvibhn.css';
import '../../css/c/cjxzckb3x.css';
import '../../css/i/i4ctr12sy.css';
import '../../css/m/m8tiflbie.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="raphvibhn"/><path clip-rule="evenodd" class="cjxzckb3x"/><path clip-rule="evenodd" class="i4ctr12sy"/><path clip-rule="evenodd" class="m8tiflbie"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:cellphone-loop-off" /></template>
