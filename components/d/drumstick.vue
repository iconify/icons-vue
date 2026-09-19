<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h3_aatb9x.css';
import '../../css/b/bkdzqdiui.css';
import '../../css/x/xebye_b2d.css';
import '../../css/i/ictw2ccqc.css';
import '../../css/l/l4se64bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="h3_aatb9x"/><ellipse transform="rotate(45 32.535 15.435)" class="bkdzqdiui"/><circle transform="rotate(45 30.06 11.398)" class="xebye_b2d"/><circle transform="rotate(45 37.132 18.47)" class="ictw2ccqc"/><circle transform="rotate(45 31.475 17.055)" class="l4se64bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:drumstick" /></template>
