<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wmmnt9jkb.css';
import '../../css/b/b2fitjben.css';
import '../../css/i/i38s-hq5f.css';
import '../../css/n/nqxug22ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wmmnt9jkb"/><path class="b2fitjben"/><path clip-rule="evenodd" class="i38s-hq5f"/><path class="nqxug22ic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:apple" /></template>
