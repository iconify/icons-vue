<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ofk9q-bmu.css';
import '../../css/h/hdr-12bxz.css';
import '../../css/b/b2-9zihvx.css';
import '../../css/r/rir49oswk.css';
import '../../css/q/qbet6fbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ofk9q-bmu wm-k"/><path class="hdr-12bxz wm-a"/><path class="b2-9zihvx wm-shadow"/><path class="rir49oswk wm-k"/><path class="qbet6fbaw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-left-engrave" /></template>
