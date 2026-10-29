<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w78uambvl.css';
import '../../css/g/gn5f4mpcl.css';
import '../../css/q/qkacyrwvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w78uambvl"/><path class="gn5f4mpcl wm-shadow"/><path class="qkacyrwvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bluetooth-engrave" /></template>
