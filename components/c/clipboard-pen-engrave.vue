<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kq5m_jrsp.css';
import '../../css/b/b3lg4q9xa.css';
import '../../css/m/mv943cb1j.css';
import '../../css/z/z32r0tbnn.css';
import '../../css/j/jljkj-bjl.css';
import '../../css/p/p88jhsbpe.css';
import '../../css/j/j10ehyblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kq5m_jrsp wm-k"/><path class="b3lg4q9xa wm-a"/><path class="mv943cb1j wm-s"/><path class="wm-shadow z32r0tbnn"/><path class="jljkj-bjl wm-k"/><path class="p88jhsbpe wm-a"/><path class="j10ehyblf wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-pen-engrave" /></template>
