<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e3gmfobmo.css';
import '../../css/n/nr9l_jbdy.css';
import '../../css/k/kej479gyu.css';
import '../../css/b/bt03i9b7n.css';
import '../../css/v/vd_y7sz1f.css';
import '../../css/g/g034bv7jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e3gmfobmo"/><path class="nr9l_jbdy wm-a"/><path class="kej479gyu wm-s"/><path class="bt03i9b7n wm-k"/><path class="vd_y7sz1f wm-a"/><path class="g034bv7jn wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-ring-sketch" /></template>
