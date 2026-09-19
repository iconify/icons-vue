<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gwp2jwycy.css';
import '../../css/p/pas470bde.css';
import '../../css/d/dt-wanbxy.css';
import '../../css/a/ay-mwcklb.css';
import '../../css/o/o_ea411kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="gwp2jwycy"/><path class="pas470bde"/><path class="dt-wanbxy"/><path class="ay-mwcklb"/><path class="o_ea411kg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:connection-box" /></template>
