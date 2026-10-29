<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zxmf3xbzu.css';
import '../../css/o/oc_p2dhlj.css';
import '../../css/q/q3ad9d2ky.css';
import '../../css/z/ziso84b9n.css';
import '../../css/u/uxoz16zip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zxmf3xbzu"/><path class="oc_p2dhlj wm-k"/><path class="q3ad9d2ky wm-a"/><path class="wm-k ziso84b9n"/><path class="uxoz16zip wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bath-sketch" /></template>
