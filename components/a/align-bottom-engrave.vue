<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eyn2r1bud.css';
import '../../css/k/keef2z3wp.css';
import '../../css/w/wjxk61s0x.css';
import '../../css/v/v_ui7pbkk.css';
import '../../css/d/dqt-8mv4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eyn2r1bud wm-k"/><path class="keef2z3wp wm-a"/><path class="wjxk61s0x wm-shadow"/><path class="v_ui7pbkk wm-k"/><path class="dqt-8mv4w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-bottom-engrave" /></template>
