<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pedgsybcp.css';
import '../../css/f/f8-pkcc1c.css';
import '../../css/e/en8bqbcrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pedgsybcp"/><path class="f8-pkcc1c"/><path class="en8bqbcrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:flip" /></template>
