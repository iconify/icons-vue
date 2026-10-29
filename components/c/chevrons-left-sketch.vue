<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sdhsa1lja.css';
import '../../css/a/aq94_1bal.css';
import '../../css/n/nh9e63xmb.css';
import '../../css/m/m3cpnbcue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sdhsa1lja wm-k"/><path class="aq94_1bal wm-a"/><path class="nh9e63xmb wm-k"/><path class="m3cpnbcue wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-left-sketch" /></template>
