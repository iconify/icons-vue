<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qy7_hlb2q.css';
import '../../css/o/owkq-n1ue.css';
import '../../css/i/ipva-ybxm.css';
import '../../css/t/t2zlwccha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qy7_hlb2q wm-k"/><path class="owkq-n1ue wm-shadow"/><path class="ipva-ybxm wm-k"/><path class="t2zlwccha wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:coffin-engrave" /></template>
