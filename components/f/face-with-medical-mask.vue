<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mr8v6_5kn.css';
import '../../css/u/uhfgxvb8v.css';
import '../../css/h/htbk-abbd.css';
import '../../css/x/xms4j1b0r.css';
import '../../css/r/rh3uwmbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mr8v6_5kn"/><path class="uhfgxvb8v"/><path class="htbk-abbd"/><path class="xms4j1b0r"/><path class="rh3uwmbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:face-with-medical-mask" /></template>
