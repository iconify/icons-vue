<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kl36rlvot.css';
import '../../css/y/y6m9ydbrm.css';
import '../../css/b/b1ti3cxbu.css';
import '../../css/l/lq_cp1bfu.css';
import '../../css/d/dp9ap3b7v.css';
import '../../css/y/ywgqm0b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kl36rlvot wm-k"/><path class="wm-a y6m9ydbrm"/><path class="b1ti3cxbu wm-shadow"/><path class="lq_cp1bfu wm-k"/><path class="dp9ap3b7v wm-k"/><path class="wm-a ywgqm0b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dhak-engrave" /></template>
