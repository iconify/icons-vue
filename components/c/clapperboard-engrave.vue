<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v8ivd-pjc.css';
import '../../css/a/aot10xncv.css';
import '../../css/t/txvu2kl1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v8ivd-pjc"/><path class="aot10xncv wm-shadow"/><path class="txvu2kl1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clapperboard-engrave" /></template>
