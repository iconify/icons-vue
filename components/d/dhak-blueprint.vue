<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/e7ro99b2e.css';
import '../../css/h/hsx_6qbkq.css';
import '../../css/l/l8de7v3ap.css';
import '../../css/z/z3dj8te5n.css';
import '../../css/l/l0axfdcpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="e7ro99b2e wm-deco"/><path class="hsx_6qbkq wm-deco"/><path class="l8de7v3ap wm-deco"/><path class="wm-k z3dj8te5n"/><path class="l0axfdcpe wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dhak-blueprint" /></template>
