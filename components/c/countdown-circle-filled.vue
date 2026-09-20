<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGn53j66wN"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="xa_h4qb2r"/><path clip-rule="evenodd" class="q_8px0bpn"/><path class="jw6gqxb1j"/><path clip-rule="evenodd" class="fwn143rdw"/><path clip-rule="evenodd" class="zbuo5kn0g"/></g></mask></defs><circle mask="url(#SVGn53j66wN)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:countdown-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.fwn143rdw {
  fill-rule: evenodd;
  d: path("M7.207 12.293a1 1 0 0 1 0 1.414l-1.5 1.5a1 1 0 0 1-1.414-1.414l1.5-1.5a1 1 0 0 1 1.414 0M13.5 9a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0v-3a1 1 0 0 1 1-1");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.jw6gqxb1j {
  d: path("M11.5 6.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0M9 8a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1.5 2.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.q_8px0bpn {
  fill-rule: evenodd;
  d: path("M9.394 14.447a1 1 0 0 0-.447-1.341l-2-1a1 1 0 1 0-.894 1.789l2 1a1 1 0 0 0 1.341-.448");
}

.xa_h4qb2r {
  fill-rule: evenodd;
  d: path("M12.5 6a1 1 0 0 1 1-1a8 8 0 1 1-8 8a1 1 0 0 1 2 0a6 6 0 1 0 6-6a1 1 0 0 1-1-1");
}

.zbuo5kn0g {
  fill-rule: evenodd;
  d: path("M17.5 13a1 1 0 0 1-1 1h-3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1");
}

</style>
