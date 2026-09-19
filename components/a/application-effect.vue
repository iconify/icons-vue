<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/btfknrzgi.css';
import '../../css/a/akwxa_yxs.css';
import '../../css/p/p5elmg96x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="btfknrzgi"/><path class="akwxa_yxs"/><path class="p5elmg96x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:application-effect" /></template>
