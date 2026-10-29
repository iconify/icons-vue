<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qdi26uumk.css';
import '../../css/z/z0uikzb1u.css';
import '../../css/e/eutcltbzm.css';
import '../../css/h/hbi65rbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qdi26uumk"/><path class="wm-a z0uikzb1u"/><path class="eutcltbzm wm-k"/><path class="hbi65rbll wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:keyboard-sketch" /></template>
