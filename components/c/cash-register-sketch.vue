<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j9nsgn3dd.css';
import '../../css/z/zpb40dbcj.css';
import '../../css/m/mp6icqbcw.css';
import '../../css/m/mhf7fy-me.css';
import '../../css/m/m2_ryiblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j9nsgn3dd"/><path class="wm-k zpb40dbcj"/><path class="mp6icqbcw wm-a"/><path class="mhf7fy-me wm-k"/><path class="m2_ryiblu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cash-register-sketch" /></template>
