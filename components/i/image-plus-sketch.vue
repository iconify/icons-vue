<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jktrt1h6c.css';
import '../../css/m/mnmd8acsd.css';
import '../../css/a/a655nzbvw.css';
import '../../css/i/iqi2kk9_g.css';
import '../../css/l/lhdead8xm.css';
import '../../css/s/s9pyjpw8b.css';
import '../../css/v/vdrbhz4zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jktrt1h6c"/><path class="mnmd8acsd wm-k"/><path class="a655nzbvw wm-a"/><path class="iqi2kk9_g wm-s"/><path class="lhdead8xm wm-k"/><path class="s9pyjpw8b wm-a"/><path class="vdrbhz4zb wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-plus-sketch" /></template>
