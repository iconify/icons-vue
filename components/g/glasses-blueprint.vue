<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a5i21bbjm.css';
import '../../css/s/szpe6lbij.css';
import '../../css/g/gbdh5hbbq.css';
import '../../css/w/w9hdm4bem.css';
import '../../css/u/uo-rcgb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a5i21bbjm wm-deco"/><path class="szpe6lbij wm-deco"/><path class="gbdh5hbbq wm-k"/><path class="w9hdm4bem wm-k"/><path class="uo-rcgb9q wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glasses-blueprint" /></template>
