<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hnut4_biv.css';
import '../../css/i/itv7kab7h.css';
import '../../css/r/rxl616bbn.css';
import '../../css/t/tx4bxklty.css';
import '../../css/d/d27ljhbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="hnut4_biv"/><path class="itv7kab7h"/><path class="rxl616bbn"/><circle class="tx4bxklty"/><circle class="d27ljhbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:game-console" /></template>
