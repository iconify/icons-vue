<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y733flb7w"/><path clip-rule="evenodd" class="lt1_q1bel"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kp3r-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lt1_q1bel {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 7.84C8 5.719 9.731 4 11.867 4h.267C14.269 4 16 5.719 16 7.84v3.165c.839.06 1.5.766 1.5 1.627v5.737c0 .9-.725 1.631-1.618 1.631H8.119c-.894 0-1.619-.73-1.619-1.631v-5.737c0-.861.662-1.566 1.5-1.627zM9 11h6V7.77C15 6.24 13.657 5 12 5S9 6.24 9 7.769zm-.966 1a.533.533 0 0 0-.534.533v5.935c0 .294.239.532.534.532h7.932a.533.533 0 0 0 .534-.533v-5.934a.533.533 0 0 0-.534-.533zM12 13.5a.5.5 0 0 0-.5.5v1q0 .065.015.125a1 1 0 1 0 .97 0A.5.5 0 0 0 12.5 15v-1a.5.5 0 0 0-.5-.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y733flb7w {
  fill: var(--svg-color--0277fd, #0277fd);
  d: path("M24 0H0v24h24z");
}

</style>
