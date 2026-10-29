<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uwk-_9bfp.css';
import '../../css/x/xvw-kacii.css';
import '../../css/q/qtmvutb-a.css';
import '../../css/o/ow5u1cc8c.css';
import '../../css/v/vxyac5iur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uwk-_9bfp wm-k"/><path class="wm-a xvw-kacii"/><path class="qtmvutb-a wm-shadow"/><path class="ow5u1cc8c wm-k"/><path class="vxyac5iur wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banana-engrave" /></template>
