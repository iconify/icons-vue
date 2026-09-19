<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lwjmshbof.css';
import '../../css/p/pmux4jffc.css';
import '../../css/c/c0ps_ubnv.css';
import '../../css/u/u4bf41b-s.css';
import '../../css/o/oc5vzqbcn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPlMXeqsm"><g class="ft5dv1b6b"><circle class="lwjmshbof"/><path class="pmux4jffc"/><circle class="c0ps_ubnv"/><circle class="u4bf41b-s"/><path class="oc5vzqbcn"/></g></mask></defs><path mask="url(#SVGPlMXeqsm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:koala-bear" /></template>
