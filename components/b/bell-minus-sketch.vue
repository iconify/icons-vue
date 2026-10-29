<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mqa-_wbaf.css';
import '../../css/k/kj_qmbbtw.css';
import '../../css/r/rzv24ii1n.css';
import '../../css/p/p5os4ng7w.css';
import '../../css/t/tq812si9s.css';
import '../../css/n/n9ntmhbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mqa-_wbaf"/><path class="kj_qmbbtw wm-a"/><path class="rzv24ii1n wm-s"/><path class="p5os4ng7w wm-k"/><path class="tq812si9s wm-a"/><path class="n9ntmhbfy wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-minus-sketch" /></template>
