<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eroup8bby.css';
import '../../css/s/sqkmwdbyf.css';
import '../../css/h/hy03qtb1b.css';
import '../../css/u/uh2h54m8i.css';
import '../../css/w/wi8hi9iwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="eroup8bby"/><path clip-rule="evenodd" class="sqkmwdbyf"/><path class="hy03qtb1b"/><path clip-rule="evenodd" class="uh2h54m8i"/><path clip-rule="evenodd" class="wi8hi9iwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:imm" /></template>
