<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGfhvpfeQg"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="ds5ly2jxw"/><path class="h5q-b7bfk"/><path clip-rule="evenodd" class="h1r1gl3hz"/></g></mask></defs><circle mask="url(#SVGfhvpfeQg)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-smiling-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ds5ly2jxw {
  fill-rule: evenodd;
  d: path("M13 20.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.ft5dv1b6b {
  fill: none;
}

.h1r1gl3hz {
  fill-rule: evenodd;
  d: path("M17.447 15.106a1 1 0 0 1 .447 1.341L17 16l.894.448v.001l-.002.003l-.003.005l-.006.013a2 2 0 0 1-.077.135q-.073.122-.21.308a4.8 4.8 0 0 1-.846.868C15.96 18.413 14.743 19 13 19s-2.96-.587-3.75-1.22a4.8 4.8 0 0 1-.847-.867a4 4 0 0 1-.286-.443l-.006-.013l-.003-.005l-.001-.003c-.001-.001-.001-.002.893-.449l-.894.447a1 1 0 1 1 1.798-.88q.025.046.1.146c.098.13.26.317.496.506c.46.368 1.243.781 2.5.781s2.04-.413 2.5-.78a2.8 2.8 0 0 0 .497-.507a2 2 0 0 0 .114-.172a1 1 0 0 1 1.336-.436");
}

.h5q-b7bfk {
  d: path("M11.5 10.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>
