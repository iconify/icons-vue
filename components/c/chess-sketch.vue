<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v1xl4fjpl.css';
import '../../css/v/vnwe1ttqq.css';
import '../../css/l/lawrsyelz.css';
import '../../css/e/e2kk_lgwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v1xl4fjpl"/><path class="vnwe1ttqq wm-k"/><path class="lawrsyelz wm-k"/><path class="e2kk_lgwx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chess-sketch" /></template>
