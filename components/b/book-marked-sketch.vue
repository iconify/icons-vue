<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k55pnmbhe.css';
import '../../css/u/ur5jsv72p.css';
import '../../css/m/m0zc6tsaa.css';
import '../../css/m/m4umu-wtt.css';
import '../../css/w/w7oqhhkbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k55pnmbhe"/><path class="ur5jsv72p wm-k"/><path class="m0zc6tsaa wm-a"/><path class="m4umu-wtt wm-k"/><path class="w7oqhhkbx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-marked-sketch" /></template>
