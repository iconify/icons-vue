<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g-847bcbd.css';
import '../../css/q/q1mq1r_ft.css';
import '../../css/u/u4hrt40ee.css';
import '../../css/h/hmkhhrbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="g-847bcbd"/><path class="q1mq1r_ft"/><path class="u4hrt40ee"/><path class="hmkhhrbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:green-new-energy" /></template>
