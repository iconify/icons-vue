<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mb0h31oir.css';
import '../../css/q/qd_hqobgv.css';
import '../../css/v/v__h_gffi.css';
import '../../css/p/pd6vc2bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mb0h31oir"/><path clip-rule="evenodd" class="qd_hqobgv"/><path clip-rule="evenodd" class="v__h_gffi"/><path class="pd6vc2bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:bell-slash" /></template>
