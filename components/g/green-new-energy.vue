<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g-847bcbd.css';
import '../../css/q/qfd3y4bqn.css';
import '../../css/f/fik22ihad.css';
import '../../css/a/ajnjn5bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="g-847bcbd"/><path class="qfd3y4bqn"/><path class="fik22ihad"/><path class="ajnjn5bpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:green-new-energy" /></template>
