<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/a459j710d.css';
import '../../css/r/rkm-xfb-q.css';
import '../../css/p/ppcrud4jg.css';
import '../../css/t/t0-jhwb6f.css';
import '../../css/w/w2clp_a8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="a459j710d"/><path class="rkm-xfb-q"/><circle class="ppcrud4jg"/><circle class="t0-jhwb6f"/><path class="w2clp_a8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:gift-bag" /></template>
