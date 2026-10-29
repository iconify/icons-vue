<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekmmp9bch.css';
import '../../css/r/rwe_4gjuh.css';
import '../../css/j/j06sm_bes.css';
import '../../css/q/q-71ghqrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekmmp9bch wm-k"/><path class="rwe_4gjuh wm-a"/><path class="j06sm_bes wm-k"/><path class="q-71ghqrx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-turban-sketch" /></template>
