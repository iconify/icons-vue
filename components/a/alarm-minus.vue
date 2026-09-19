<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2_gkeb7e.css';
import '../../css/g/g-btfib-b.css';
import '../../css/t/t8uudi0mb.css';
import '../../css/q/qnfpgub0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n2_gkeb7e"/><path class="g-btfib-b"/><path class="t8uudi0mb"/><path class="qnfpgub0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:alarm-minus" /></template>
