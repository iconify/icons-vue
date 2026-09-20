<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bivr09fnn.css';
import '../../css/v/vjo6m_bwu.css';
import '../../css/i/ihtd0j-_z.css';
import '../../css/x/xeugi8bqs.css';
import '../../css/d/d_mpy6b4b.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="bivr09fnn"/><path clip-rule="evenodd" class="vjo6m_bwu"/><path clip-rule="evenodd" class="ihtd0j-_z"/><path clip-rule="evenodd" class="xeugi8bqs"/><path clip-rule="evenodd" class="d_mpy6b4b"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:enter-off" /></template>
