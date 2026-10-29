<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/ba0ujbcbx.css';
import '../../css/q/qmveuub9a.css';
import '../../css/x/xrmjuk50y.css';
import '../../css/t/tdo3ihb9n.css';
import '../../css/a/avtmk6b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ba0ujbcbx"/><path class="qmveuub9a wm-k"/><path class="wm-a xrmjuk50y"/><path class="tdo3ihb9n wm-k"/><path class="avtmk6b7z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hand-coins-sketch" /></template>
