<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/p/pnbxzjb2y.css';
import '../../css/u/ux9pwvqah.css';
import '../../css/x/x6tlt5s8q.css';
import '../../css/d/dqrzf1bnz.css';
import '../../css/f/f7k5plbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="pnbxzjb2y"/><circle class="ux9pwvqah"/><circle class="x6tlt5s8q"/></g><path class="dqrzf1bnz"/><path clip-rule="evenodd" class="f7k5plbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:division-print" /></template>
