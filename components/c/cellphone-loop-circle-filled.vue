<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGAayDldAG"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="j3037bcit"/><path clip-rule="evenodd" class="os-ibivrc"/><path clip-rule="evenodd" class="gyxujzbjs"/><path clip-rule="evenodd" class="bznq5q1dy"/></g></mask></defs><circle mask="url(#SVGAayDldAG)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cellphone-loop-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bznq5q1dy {
  fill-rule: evenodd;
  d: path("M10.347 12.38a2.193 2.193 0 1 0-2.567 3.555a2.193 2.193 0 0 0 2.567-3.555m-4.683-.677a4.193 4.193 0 1 1 1.827 6.342L5.4 20.942a1 1 0 1 1-1.622-1.17l2.091-2.898a4.195 4.195 0 0 1-.205-5.17");
}

.ft5dv1b6b {
  fill: none;
}

.gyxujzbjs {
  fill-rule: evenodd;
  d: path("M8.5 6.5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3H11A2.5 2.5 0 0 1 8.5 20v-.5a1 1 0 1 1 2 0v.5a.5.5 0 0 0 .5.5h7.5a1 1 0 0 0 1-1v-13a1 1 0 0 0-1-1h-7a1 1 0 0 0-1 1v2.25a1 1 0 0 1-2 0z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.j3037bcit {
  d: path("M15.675 18.138a.675.675 0 1 1-1.35 0a.675.675 0 0 1 1.35 0");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.os-ibivrc {
  fill-rule: evenodd;
  d: path("M15 17.963a.175.175 0 1 0 0 .35a.175.175 0 0 0 0-.35m-1.175.174a1.175 1.175 0 1 1 2.35 0a1.175 1.175 0 0 1-2.35 0");
}

</style>
