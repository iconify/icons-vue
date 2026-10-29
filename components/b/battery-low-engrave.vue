<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t-ku3dm-z.css';
import '../../css/w/wlj1vgb0q.css';
import '../../css/x/xmzujebsj.css';
import '../../css/n/nn2sdrbun.css';
import '../../css/g/go5n_1h8p.css';
import '../../css/j/jp-9hnyip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t-ku3dm-z wm-k"/><path class="wlj1vgb0q wm-a"/><path class="wm-shadow xmzujebsj"/><path class="nn2sdrbun wm-k"/><path class="go5n_1h8p wm-a"/><path class="jp-9hnyip wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:battery-low-engrave" /></template>
