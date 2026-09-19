<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__s2g6zp.css';
import '../../css/l/ln7cyvcfw.css';
import '../../css/z/z2xr0pb1c.css';
import '../../css/w/wpmk60uqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="ln7cyvcfw"/><rect class="z2xr0pb1c"/><rect class="wpmk60uqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:divide-bold" /></template>
