<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eq69c5b1k.css';
import '../../css/d/dk-6nkmfw.css';
import '../../css/v/vgfot6b_w.css';
import '../../css/u/u5k-jlbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eq69c5b1k wm-k"/><path class="dk-6nkmfw wm-shadow"/><path class="vgfot6b_w wm-k"/><path class="u5k-jlbkg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gingerbread-man-engrave" /></template>
