<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/d/djd1-ccrl.css';
import '../../css/u/u23x9_bve.css';
import '../../css/w/w8an2-hht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="djd1-ccrl"/><path class="u23x9_bve"/><path class="w8an2-hht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:bb" /></template>
