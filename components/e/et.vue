<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/b/b1zl1-bpc.css';
import '../../css/s/s_38i5s8e.css';
import '../../css/k/kjecq87zs.css';
import '../../css/l/lsadno_3x.css';
import '../../css/d/dhnp3_bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="b1zl1-bpc"/><path class="s_38i5s8e"/><path class="kjecq87zs"/><circle class="lsadno_3x"/><path class="dhnp3_bnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:et" /></template>
