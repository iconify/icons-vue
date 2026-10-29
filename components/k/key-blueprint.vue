<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/ysznytbju.css';
import '../../css/c/c6vs_ccxk.css';
import '../../css/p/pbtr10c0j.css';
import '../../css/l/l2ogbdbpz.css';
import '../../css/w/w5jtgj_4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco ysznytbju"/><path class="c6vs_ccxk wm-deco"/><path class="pbtr10c0j wm-deco"/><path class="l2ogbdbpz wm-k"/><path class="w5jtgj_4y wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-blueprint" /></template>
