<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/ze__q9b-y.css';
import '../../css/p/pxp48iyht.css';
import '../../css/m/msgncjdxc.css';
import '../../css/b/bhyjiupcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ze__q9b-y"/><path class="pxp48iyht"/><path class="msgncjdxc"/><path class="bhyjiupcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:data-lock" /></template>
