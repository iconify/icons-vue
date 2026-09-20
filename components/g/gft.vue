<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s4i7eyblh"/><path class="ubwa91bxj"/><path class="f8lld1x7i"/><path class="pj4qncqev"/><path class="g9l2ftb9w"/><path class="uya3ufbae"/><path clip-rule="evenodd" class="l974m1anv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gft" /></template>
<style>
.f8lld1x7i {
  fill: var(--svg-color--4ed9ab, #4ed9ab);
  d: path("M8 17.8v-5.665l4.185-7.455l3.55 6.95z");
}

.ft5dv1b6b {
  fill: none;
}

.g9l2ftb9w {
  fill: var(--svg-color--4cdac7, #4cdac7);
  d: path("M16.045 11.345L14.6 8.52l4.28.915z");
}

.l974m1anv {
  fill: var(--svg-color--4edbc8, #4edbc8);
  fill-rule: evenodd;
  d: path("M20 7.5L12 3L4 7.5v9l8 4.5l8-4.5zm-1 .545l-7-3.96l-7 3.96v7.905l7 3.96l7-3.96z");
}

.pj4qncqev {
  fill: var(--svg-color--3b896a, #3b896a);
  d: path("m16.795 17.916l-4.69-2.63l3.79-2.89z");
}

.s4i7eyblh {
  fill: var(--svg-color--dff8da, #dff8da);
  d: path("m12 3.895l7.205 4.05v8.11l-7.2 4.05l-7.21-4.05v-8.11L12 3.9z");
}

.ubwa91bxj {
  fill: var(--svg-color--3b896a, #3b896a);
  d: path("m6.49 12.745l-2.15-2.46l3.816-.72z");
}

.uya3ufbae {
  fill: var(--svg-color--4ed9ab, #4ed9ab);
  d: path("M7.35 11.71L5.2 9.25l3.816-.72z");
}

</style>
