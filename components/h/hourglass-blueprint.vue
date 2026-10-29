<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/u-1mpi1_y.css';
import '../../css/b/bo8ys6w-i.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/a/aux2szb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="u-1mpi1_y wm-deco"/><path class="bo8ys6w-i wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="aux2szb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hourglass-blueprint" /></template>
