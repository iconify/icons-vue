<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vpxvdibwg.css';
import '../../css/i/i8ycrbbjm.css';
import '../../css/j/jyhp0fz-d.css';
import '../../css/c/cw36_6mco.css';
import '../../css/s/s-dcxqbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vpxvdibwg wm-k"/><path class="i8ycrbbjm wm-a"/><path class="jyhp0fz-d wm-shadow"/><path class="cw36_6mco wm-a"/><path class="s-dcxqbqn wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-line-engrave" /></template>
