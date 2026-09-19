<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r3pi_yb7o.css';
import '../../css/s/srn6uhb7n.css';
import '../../css/q/q527_cc6o.css';
import '../../css/p/p_n3i_b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r3pi_yb7o"/><path class="srn6uhb7n"/><path clip-rule="evenodd" class="q527_cc6o"/><path class="p_n3i_b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-add-outline" /></template>
