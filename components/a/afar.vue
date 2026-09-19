<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/l/lb-lfcbse.css';
import '../../css/h/hzvbg3bbn.css';
import '../../css/u/ul3ge0b9c.css';
import '../../css/h/hc3wxtbfo.css';
import '../../css/c/cywyir7_w.css';
import '../../css/x/xc48zglrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsAfar0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsAfar0)"><path class="lb-lfcbse"/><path class="hzvbg3bbn"/><path class="ul3ge0b9c"/><path class="hc3wxtbfo"/><path class="cywyir7_w"/><path class="xc48zglrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:afar" /></template>
