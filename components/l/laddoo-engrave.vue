<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aiz3dcjyo.css';
import '../../css/c/c-wcphrmv.css';
import '../../css/q/qmnox1bpl.css';
import '../../css/z/z-xy10bpg.css';
import '../../css/v/v1r6jvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aiz3dcjyo"/><path class="c-wcphrmv wm-shadow"/><path class="qmnox1bpl"/><path class="z-xy10bpg"/><path class="v1r6jvbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:laddoo-engrave" /></template>
