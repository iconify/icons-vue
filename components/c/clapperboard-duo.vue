<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dawizt-sr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gxeo900vz.css';
import '../../css/x/xmonvmbep.css';
import '../../css/p/p543wbb6j.css';
import '../../css/w/w5qtwlbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dawizt-sr secondary"/><g class="dt0cm9dhy primary"><path class="gxeo900vz"/><path class="xmonvmbep"/><path class="p543wbb6j"/><path class="w5qtwlbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clapperboard-duo" /></template>
