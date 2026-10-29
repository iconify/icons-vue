<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eh36e2b7w.css';
import '../../css/p/p3fp7ob2a.css';
import '../../css/q/qz6uo5ozb.css';
import '../../css/t/trosep5nc.css';
import '../../css/l/lxqvghd5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eh36e2b7w wm-k"/><path class="p3fp7ob2a wm-k"/><path class="qz6uo5ozb wm-a"/><path class="trosep5nc wm-a"/><path class="lxqvghd5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dumpling-sketch" /></template>
