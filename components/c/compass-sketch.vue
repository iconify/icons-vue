<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hpb1aw6wk.css';
import '../../css/u/udv9a5ayb.css';
import '../../css/a/av4380b0t.css';
import '../../css/y/yeorqghpo.css';
import '../../css/g/g8hg9gbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hpb1aw6wk wm-a"/><path class="udv9a5ayb wm-k"/><path class="av4380b0t wm-k"/><path class="wm-a yeorqghpo"/><circle class="g8hg9gbmt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:compass-sketch" /></template>
