<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mwei4gkkt.css';
import '../../css/d/du887ss5t.css';
import '../../css/n/nr9v46bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mwei4gkkt"/><path class="du887ss5t"/><path class="nr9v46bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:binoculars-1" /></template>
