<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wwai64oxb.css';
import '../../css/b/b2c9mzmwk.css';
import '../../css/m/m0qgth23d.css';
import '../../css/p/pdoe7fa1e.css';
import '../../css/h/h7a9wibzd.css';
import '../../css/c/cu7wb8t0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k wwai64oxb"/><path class="b2c9mzmwk wm-a"/><path class="m0qgth23d wm-shadow"/><path class="pdoe7fa1e wm-a"/><path class="h7a9wibzd wm-k"/><path class="cu7wb8t0f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:love-lock-engrave" /></template>
