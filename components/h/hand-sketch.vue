<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rf8yh-27v.css';
import '../../css/l/llsjouo2v.css';
import '../../css/g/g_sh4b3bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rf8yh-27v"/><path class="llsjouo2v"/><path class="g_sh4b3bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hand-sketch" /></template>
