<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uu-llwbjg.css';
import '../../css/s/s_8ird94j.css';
import '../../css/k/ki4c-rmpi.css';
import '../../css/v/vsn4cuk_g.css';
import '../../css/w/w0k34vd7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uu-llwbjg"/><path class="s_8ird94j wm-k"/><path class="ki4c-rmpi wm-a"/><path class="vsn4cuk_g wm-k"/><path class="w0k34vd7f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hammer-sketch" /></template>
