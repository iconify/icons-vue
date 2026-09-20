<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx25r1_5p.css';
import '../../css/u/u0vm4qb0c.css';
import '../../css/u/uodjfruxd.css';
import '../../css/l/lw91y0bks.css';
import '../../css/q/qs9xtfamj.css';
import '../../css/r/rl_g63vue.css';
import '../../css/k/k2ug-2r8g.css';
import '../../css/m/msf_1xiol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g clip-rule="evenodd" class="gx25r1_5p"><path class="u0vm4qb0c"/><path class="uodjfruxd"/><path class="lw91y0bks"/><path class="qs9xtfamj"/></g><g clip-rule="evenodd" class="gx25r1_5p"><path class="rl_g63vue"/><path class="k2ug-2r8g"/><path class="msf_1xiol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:facetime" /></template>
