<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xi8jmuqdy"/><path class="x8zeu6bvx"/><path class="mwlcle2xd"/><path class="lphabqx9t"/><path class="nbyjmcbnx"/><path class="a8gciyngb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-central-african-republic" /></template>
<style>
.a8gciyngb {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("m16.559 14.425l-3.439.004l-1.07-3.476l-1.054 3.476l-3.438-.004l2.786 2.116l-1.081 3.453l2.797-2.146l2.799 2.146l-1.085-3.453z");
}

.lphabqx9t {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M64 43H0c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11");
}

.mwlcle2xd {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 32h64v11H0z");
}

.nbyjmcbnx {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M27 10h10v44H27z");
}

.x8zeu6bvx {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 21h64v11H0z");
}

.xi8jmuqdy {
  fill: var(--svg-color--003893, #003893);
  d: path("M0 21h64c0-6.075-3.373-11-10-11H10C3.373 10 0 14.925 0 21");
}

</style>
