<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pqgcbcbrc.css';
import '../../css/x/x1br9q1lf.css';
import '../../css/b/b9guywupb.css';
import '../../css/o/ohf_mjbft.css';
import '../../css/k/k5a1jgb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="pqgcbcbrc"/><path class="x1br9q1lf"/><path class="b9guywupb"/><path class="ohf_mjbft"/><path class="k5a1jgb-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:game-handle" /></template>
