<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tge36xbah.css';
import '../../css/p/pvql17bze.css';
import '../../css/k/kugyku2sr.css';
import '../../css/z/zvz-m9brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tge36xbah"/><path class="pvql17bze"/><path class="kugyku2sr wm-k"/><path class="wm-a zvz-m9brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cookie-sketch" /></template>
