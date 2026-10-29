<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bvn0ecifr.css';
import '../../css/z/z2st76yla.css';
import '../../css/y/ylb7kmbxq.css';
import '../../css/w/w0-632-cs.css';
import '../../css/j/jam8cccqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bvn0ecifr wm-k"/><path class="wm-a z2st76yla"/><path class="wm-shadow ylb7kmbxq"/><path class="w0-632-cs wm-k"/><path class="jam8cccqq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chinese-knot-engrave" /></template>
