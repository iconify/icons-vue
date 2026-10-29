<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xc-0o323g.css';
import '../../css/f/fy6bo93ja.css';
import '../../css/o/oxzt-_bip.css';
import '../../css/l/lzvj-hbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xc-0o323g"/><path class="fy6bo93ja wm-a"/><path class="oxzt-_bip wm-k"/><path class="lzvj-hbzd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-sketch" /></template>
