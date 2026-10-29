<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q0vto-bmm.css';
import '../../css/q/q3_7_ccpf.css';
import '../../css/a/atm8lqble.css';
import '../../css/a/ae-e09b3w.css';
import '../../css/p/p4k_t7lwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q0vto-bmm wm-k"/><path class="q3_7_ccpf wm-a"/><path class="atm8lqble wm-shadow"/><path class="ae-e09b3w wm-k"/><path class="p4k_t7lwr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-right-engrave" /></template>
