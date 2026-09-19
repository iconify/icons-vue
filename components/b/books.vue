<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nwz1onbzm.css';
import '../../css/u/ujwe30bnu.css';
import '../../css/q/q9h09_bxm.css';
import '../../css/s/sdsw_p56g.css';
import '../../css/v/vu1pckbyw.css';
import '../../css/y/yrp160_mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="nwz1onbzm"/><path class="ujwe30bnu"/><rect class="q9h09_bxm"/><path class="sdsw_p56g"/><path clip-rule="evenodd" class="vu1pckbyw"/><path class="yrp160_mj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:books" /></template>
