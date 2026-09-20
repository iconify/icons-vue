<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-nm9bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-question-outline-sharp" /></template>
<style>
.u4-nm9bhw {
  fill: currentColor;
  d: path("M3 16V8zm13.88 1H2V7h13.66q-.212.227-.385.467T14.967 8H3v8h13.539q.011.279.102.532q.092.252.24.468m2.995-.855q.182-.181.182-.453q0-.27-.182-.462q-.182-.191-.453-.191t-.453.19t-.181.463t.181.453t.453.182t.453-.182m-.884-2.503h.868q.019-.255.048-.496q.028-.24.153-.446q.17-.267.369-.483t.41-.427q.425-.424.732-.905t.307-1.114q0-.935-.697-1.555t-1.682-.62q-.815 0-1.479.435q-.663.434-.971 1.18l.775.333q.227-.5.672-.806q.445-.305 1.003-.305q.621 0 1.076.377q.455.376.455.973q0 .483-.279.878t-.617.708q-.276.256-.505.509q-.23.253-.405.584q-.13.292-.182.578q-.05.285-.05.602");
}

</style>
