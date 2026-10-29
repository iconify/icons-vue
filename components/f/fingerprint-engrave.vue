<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bhrl3db-r.css';
import '../../css/i/immdxpb6m.css';
import '../../css/q/q-ca_6bsx.css';
import '../../css/w/w4fklccqs.css';
import '../../css/x/x2wfbzbcz.css';
import '../../css/f/fkvw3pbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bhrl3db-r wm-k"/><path class="immdxpb6m wm-a"/><path class="q-ca_6bsx wm-shadow"/><path class="w4fklccqs wm-k"/><path class="wm-a x2wfbzbcz"/><path class="fkvw3pbgy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fingerprint-engrave" /></template>
