<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g2e3-xb4j.css';
import '../../css/j/jfgjanxpp.css';
import '../../css/o/oqflbw88g.css';
import '../../css/o/ovtvrgkrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="g2e3-xb4j"/><circle class="jfgjanxpp"/><circle class="oqflbw88g"/><path class="ovtvrgkrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:every-user" /></template>
