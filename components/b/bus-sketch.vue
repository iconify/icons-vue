<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gg-mv2bgo.css';
import '../../css/q/q0-i_05yv.css';
import '../../css/x/xxw3a2byj.css';
import '../../css/p/pgfe_0kpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gg-mv2bgo"/><path class="q0-i_05yv wm-k"/><path class="wm-k xxw3a2byj"/><path class="pgfe_0kpr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bus-sketch" /></template>
