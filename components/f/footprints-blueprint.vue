<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dt3yg1qsa.css';
import '../../css/t/tsa86mbae.css';
import '../../css/y/ywk5os59u.css';
import '../../css/y/ywlhoqbsn.css';
import '../../css/k/k26yyvc5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dt3yg1qsa wm-deco"/><path class="tsa86mbae wm-deco"/><path class="wm-deco ywk5os59u"/><path class="wm-k ywlhoqbsn"/><path class="k26yyvc5e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:footprints-blueprint" /></template>
