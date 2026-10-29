<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/az1pmbcop.css';
import '../../css/n/nq451z9tv.css';
import '../../css/w/wkqr97bjn.css';
import '../../css/h/hn4n2eqzu.css';
import '../../css/w/wz_hfyb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="az1pmbcop"/><path class="nq451z9tv wm-k"/><path class="wkqr97bjn wm-a"/><path class="hn4n2eqzu wm-k"/><path class="wm-a wz_hfyb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-bald-sketch" /></template>
