<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y8egdlb1z.css';
import '../../css/x/x3ru08b-k.css';
import '../../css/e/egn7tzbhc.css';
import '../../css/c/c5b0y0tyz.css';
import '../../css/b/b5x9xi0bu.css';
import '../../css/w/w_iteobnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y8egdlb1z"/><path class="wm-a x3ru08b-k"/><path class="egn7tzbhc wm-shadow"/><path class="c5b0y0tyz wm-k"/><path class="b5x9xi0bu wm-a"/><path class="w_iteobnw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:copy-check-engrave" /></template>
