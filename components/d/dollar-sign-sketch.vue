<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xyhicqlan.css';
import '../../css/s/s24l1zlnp.css';
import '../../css/g/gu72yj-en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xyhicqlan"/><path class="s24l1zlnp wm-k"/><path class="gu72yj-en wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dollar-sign-sketch" /></template>
