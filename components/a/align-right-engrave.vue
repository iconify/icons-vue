<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kcbgbfb1b.css';
import '../../css/o/opnejxbao.css';
import '../../css/t/toalvz3ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kcbgbfb1b"/><path class="opnejxbao wm-shadow"/><path class="toalvz3ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-right-engrave" /></template>
