<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/a/aq31iu2el.css';
import '../../css/i/ifr_y32zs.css';
import '../../css/c/cjgizhsau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="aq31iu2el"/><path class="ifr_y32zs"/><path class="cjgizhsau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-atlas" /></template>
