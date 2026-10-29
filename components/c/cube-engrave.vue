<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xt-tyur9a.css';
import '../../css/r/ra9lelbaj.css';
import '../../css/i/inmgn9b1s.css';
import '../../css/f/f1iyce6_y.css';
import '../../css/e/ev6-t-xbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xt-tyur9a"/><path class="ra9lelbaj wm-a"/><path class="inmgn9b1s wm-shadow"/><path class="f1iyce6_y wm-k"/><path class="ev6-t-xbj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-engrave" /></template>
