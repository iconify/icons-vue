<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wjmw4zjys.css';
import '../../css/r/rlucojbsu.css';
import '../../css/j/j_kh__upk.css';
import '../../css/u/uh0pnrb4t.css';
import '../../css/w/wjck06tsq.css';
import '../../css/j/j4sw7l1ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wjmw4zjys wm-k"/><path class="rlucojbsu wm-a"/><path class="j_kh__upk wm-s"/><path class="uh0pnrb4t wm-k"/><path class="wjck06tsq wm-a"/><path class="j4sw7l1ua wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lotus-sketch" /></template>
