<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e0pazubmt.css';
import '../../css/s/si5nizbso.css';
import '../../css/y/ypj-nwmud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e0pazubmt"/><path clip-rule="evenodd" class="si5nizbso"/><path class="ypj-nwmud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:internal-reduction" /></template>
