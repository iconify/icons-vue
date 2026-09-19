<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/ydeugkbob.css';
import '../../css/u/umtsztb2x.css';
import '../../css/f/f64a49b2p.css';
import '../../css/j/jr9v2-bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ydeugkbob"/><path class="umtsztb2x"/><path class="f64a49b2p"/><path class="jr9v2-bwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:brdige-three" /></template>
