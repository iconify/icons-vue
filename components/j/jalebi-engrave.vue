<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y_cprfkpo.css';
import '../../css/c/chucnnbnc.css';
import '../../css/q/qt3_ghwjq.css';
import '../../css/v/vg2dc9z-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y_cprfkpo"/><path class="chucnnbnc wm-shadow"/><path class="qt3_ghwjq wm-k"/><path class="vg2dc9z-o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jalebi-engrave" /></template>
