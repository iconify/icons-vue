<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zm_b_i0vf.css';
import '../../css/e/exsqqdbgk.css';
import '../../css/v/v62ndkb9o.css';
import '../../css/f/fq34ly3dk.css';
import '../../css/f/f4wn345na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zm_b_i0vf"/><path class="exsqqdbgk wm-a"/><path class="v62ndkb9o wm-shadow"/><path class="fq34ly3dk wm-k"/><path class="f4wn345na wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gauge-engrave" /></template>
