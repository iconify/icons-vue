<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ee60chbki.css';
import '../../css/b/b3yv8vu-n.css';
import '../../css/p/ppte9cccs.css';
import '../../css/x/xzc8q_bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ee60chbki wm-k"/><path class="b3yv8vu-n wm-k"/><path class="ppte9cccs wm-a"/><path class="wm-s xzc8q_bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:camera-off-sketch" /></template>
