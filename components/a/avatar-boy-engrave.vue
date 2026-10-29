<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spzl3f68r.css';
import '../../css/i/i0o3y5bln.css';
import '../../css/j/jfsu2ygwb.css';
import '../../css/b/bd9iuybie.css';
import '../../css/f/faaiuubbc.css';
import '../../css/r/ryfqb9b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spzl3f68r wm-k"/><path class="i0o3y5bln wm-a"/><path class="jfsu2ygwb wm-shadow"/><path class="bd9iuybie wm-k"/><path class="faaiuubbc wm-k"/><path class="ryfqb9b2g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-boy-engrave" /></template>
