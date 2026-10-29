<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/m_5_1y9wc.css';
import '../../css/q/q_twvabdb.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/s/spdwecb9f.css';
import '../../css/p/p-al8lwyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="m_5_1y9wc wm-deco"/><path class="q_twvabdb wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="spdwecb9f wm-k"/><path class="p-al8lwyr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cable-blueprint" /></template>
