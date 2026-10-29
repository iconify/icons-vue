<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r0k_789eh.css';
import '../../css/z/zgq5wtbpl.css';
import '../../css/k/k119jwb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r0k_789eh wm-k"/><path class="wm-k zgq5wtbpl"/><path class="k119jwb1b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bitcoin-sketch" /></template>
