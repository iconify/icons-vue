<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rb-ki7sjk.css';
import '../../css/h/h-oc6j79l.css';
import '../../css/e/enkc8mbld.css';
import '../../css/s/s-717su3i.css';
import '../../css/l/lhm2uccse.css';
import '../../css/d/ddurq_bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rb-ki7sjk wm-deco"/><path class="h-oc6j79l wm-deco"/><path class="enkc8mbld wm-deco"/><path class="s-717su3i wm-k"/><path class="lhm2uccse wm-a"/><path class="ddurq_bhk wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-blueprint" /></template>
