<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnhk7kbjm.css';
import '../../css/i/iihwlg_dd.css';
import '../../css/t/tuh-5wb_m.css';
import '../../css/h/hrdr1eb-g.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/u/utit9ub1r.css';
import '../../css/k/k1noz-wad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bnhk7kbjm"/><path class="iihwlg_dd"/><path class="tuh-5wb_m"/><path class="hrdr1eb-g"/><g class="brzn_0bpr"><path class="utit9ub1r"/><path class="k1noz-wad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:jellyfin" /></template>
