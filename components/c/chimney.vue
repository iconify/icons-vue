<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mn8w30d0i.css';
import '../../css/s/st9u1u3tq.css';
import '../../css/h/h8ey_rjec.css';
import '../../css/z/zi7nydz_s.css';
import '../../css/r/rcdnxiqxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mn8w30d0i"/><path class="st9u1u3tq"/><path class="h8ey_rjec"/><path class="zi7nydz_s"/><path class="rcdnxiqxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chimney" /></template>
