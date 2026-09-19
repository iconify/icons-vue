<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/n/nbm684d5v.css';
import '../../css/c/c5j5lzb8g.css';
import '../../css/g/gyjw88vlv.css';
import '../../css/w/wdvsx9m5t.css';
import '../../css/o/oc353sfwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="nbm684d5v"/><path class="c5j5lzb8g"/><path class="gyjw88vlv"/><path class="wdvsx9m5t"/><path class="oc353sfwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:layout-three" /></template>
