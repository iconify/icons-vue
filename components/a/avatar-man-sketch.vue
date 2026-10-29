<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/we_b5psao.css';
import '../../css/s/ssp0-h_op.css';
import '../../css/c/c0cyspb-h.css';
import '../../css/s/sjr0g6bpm.css';
import '../../css/q/q7buc2b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="we_b5psao wm-k"/><path class="ssp0-h_op wm-k"/><path class="c0cyspb-h wm-k"/><path class="sjr0g6bpm wm-k"/><path class="q7buc2b6x wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-sketch" /></template>
