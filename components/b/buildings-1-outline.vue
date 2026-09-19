<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bv6k9163z.css';
import '../../css/v/v5_422bjr.css';
import '../../css/s/svl8bismt.css';
import '../../css/n/n8_nc4bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bv6k9163z"/><path clip-rule="evenodd" class="v5_422bjr"/><path class="svl8bismt"/><path clip-rule="evenodd" class="n8_nc4bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:buildings-1-outline" /></template>
