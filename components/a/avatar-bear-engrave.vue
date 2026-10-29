<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/ti_-bgbup.css';
import '../../css/s/svnjt8bpr.css';
import '../../css/m/mdvkx-geo.css';
import '../../css/u/uxz8njb2w.css';
import '../../css/i/i-oq5ub8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ti_-bgbup wm-k"/><path class="svnjt8bpr wm-shadow"/><path class="mdvkx-geo wm-k"/><path class="uxz8njb2w wm-k"/><path class="i-oq5ub8f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-bear-engrave" /></template>
