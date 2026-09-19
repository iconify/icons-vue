<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6yze9bve.css';
import '../../css/d/dmatdn5xb.css';
import '../../css/n/nzb9c50ih.css';
import '../../css/g/g89kkeb5g.css';
import '../../css/p/ptdsbkbld.css';
import '../../css/l/lpjqmxrze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="x6yze9bve"/><path class="dmatdn5xb"/><path class="nzb9c50ih"/><path class="g89kkeb5g"/><path class="ptdsbkbld"/><path class="lpjqmxrze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-group-duo" /></template>
