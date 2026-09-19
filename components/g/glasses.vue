<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/aogaj5_aa.css';
import '../../css/m/mtqe-rb2m.css';
import '../../css/i/il6_1tbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="aogaj5_aa"/><circle class="mtqe-rb2m"/><path class="il6_1tbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:glasses" /></template>
