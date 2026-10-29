<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ev6ijubpd.css';
import '../../css/h/hm6zcabmy.css';
import '../../css/u/u1-3bgbet.css';
import '../../css/n/nemtfibtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ev6ijubpd wm-k"/><path class="hm6zcabmy wm-a"/><path class="u1-3bgbet wm-k"/><path class="nemtfibtm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-afro-sketch" /></template>
