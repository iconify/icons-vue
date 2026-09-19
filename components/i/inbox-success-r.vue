<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/h/h629go4ys.css';
import '../../css/u/uc8kr5rtb.css';
import '../../css/e/e95ct9bzp.css';
import '../../css/x/xov-5e-gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="h629go4ys"/><path class="uc8kr5rtb"/><path class="e95ct9bzp"/><path class="xov-5e-gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:inbox-success-r" /></template>
