<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/frgdf8bal.css';
import '../../css/t/tnf2-2b1v.css';
import '../../css/z/ze_s10bqg.css';
import '../../css/z/zbsyr1dde.css';
import '../../css/f/fu-yhsexq.css';
import '../../css/d/d5ox4i4-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="frgdf8bal wm-k"/><path class="tnf2-2b1v wm-a"/><path class="wm-shadow ze_s10bqg"/><path class="wm-k zbsyr1dde"/><path class="fu-yhsexq wm-k"/><path class="d5ox4i4-t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hospital-engrave" /></template>
