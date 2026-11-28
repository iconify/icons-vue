<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owsvk_bvn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qgtn8_bwm.css';
import '../../css/r/rbz-yyb4g.css';
import '../../css/u/u5bgt-21q.css';
import '../../css/j/jb16clm3j.css';
import '../../css/k/kv1n0m0wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owsvk_bvn secondary"/><g class="dt0cm9dhy primary"><path class="qgtn8_bwm"/><path class="rbz-yyb4g"/><path class="u5bgt-21q"/><path class="jb16clm3j"/><path class="kv1n0m0wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lighthouse-duo" /></template>
