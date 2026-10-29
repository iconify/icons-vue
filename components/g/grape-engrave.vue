<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lx8guvb-i.css';
import '../../css/w/wqvj56bhj.css';
import '../../css/e/eo_oo5b2r.css';
import '../../css/l/lhyb3bbbn.css';
import '../../css/x/x2f5ebbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lx8guvb-i wm-k"/><path class="wm-a wqvj56bhj"/><path class="eo_oo5b2r wm-shadow"/><path class="lhyb3bbbn wm-k"/><path class="wm-a x2f5ebbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:grape-engrave" /></template>
