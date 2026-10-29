<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/epjrbcbmn.css';
import '../../css/g/g442iwe_t.css';
import '../../css/d/dfr8kabwp.css';
import '../../css/o/omdwggbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="epjrbcbmn wm-deco"/><path class="g442iwe_t wm-deco"/><path class="dfr8kabwp wm-k"/><path class="omdwggbcq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bitcoin-blueprint" /></template>
