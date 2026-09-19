<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n6imsr9dw.css';
import '../../css/i/i5f9tcbzd.css';
import '../../css/m/m98ffac6h.css';
import '../../css/c/cwv2k7btb.css';
import '../../css/r/rmiv40bur.css';
import '../../css/q/qrm756b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n6imsr9dw"/><path class="i5f9tcbzd"/><path clip-rule="evenodd" class="m98ffac6h"/><path clip-rule="evenodd" class="cwv2k7btb"/><path class="rmiv40bur"/><path clip-rule="evenodd" class="qrm756b2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:disc-outline" /></template>
