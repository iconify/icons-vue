<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ru62tcnel.css';
import '../../css/m/mm8lcj-5x.css';
import '../../css/p/pkn_w0fwn.css';
import '../../css/s/s1r0ezbnv.css';
import '../../css/s/shte9bcuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ru62tcnel wm-k"/><path class="mm8lcj-5x wm-a"/><path class="pkn_w0fwn wm-shadow"/><path class="s1r0ezbnv wm-k"/><path class="shte9bcuj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-engrave" /></template>
