<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/t1edgcb6p.css';
import '../../css/l/lw2u413yi.css';
import '../../css/d/ds3o1_brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="t1edgcb6p"/><path class="lw2u413yi"/><path class="ds3o1_brx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:album" /></template>
