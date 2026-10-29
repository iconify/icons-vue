<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ru62tcnel.css';
import '../../css/m/mm8lcj-5x.css';
import '../../css/j/jx29elb2u.css';
import '../../css/x/xr60duiqq.css';
import '../../css/s/s1r0ezbnv.css';
import '../../css/s/shte9bcuj.css';
import '../../css/u/up4lun9xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ru62tcnel wm-k"/><path class="mm8lcj-5x wm-a"/><path class="jx29elb2u wm-s"/><path class="wm-shadow xr60duiqq"/><path class="s1r0ezbnv wm-k"/><path class="shte9bcuj wm-a"/><path class="up4lun9xh wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-ring-engrave" /></template>
