<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e0pazubmt.css';
import '../../css/w/wn5rh4bnl.css';
import '../../css/y/ypj-nwmud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e0pazubmt"/><path clip-rule="evenodd" class="wn5rh4bnl"/><path class="ypj-nwmud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:internal-reduction" /></template>
