<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qzj8rgbse.css';
import '../../css/u/u_bdg8bwm.css';
import '../../css/n/nbj7ro57z.css';
import '../../css/a/a1oh0abvp.css';
import '../../css/i/i3-2a2b5x.css';
import '../../css/p/peqi26xdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qzj8rgbse wm-deco"/><path class="u_bdg8bwm wm-deco"/><path class="nbj7ro57z wm-deco"/><path class="a1oh0abvp wm-k"/><path class="i3-2a2b5x wm-k"/><path class="peqi26xdy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-cat-blueprint" /></template>
