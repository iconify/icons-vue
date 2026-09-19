<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y49ee0b2y"/><g class="n1mjunbsu"><circle class="c58hmybvv"/><path class="gho3h6r1y"/><path class="vcyc_nq8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:baby-symbol" /></template>
<style>
.c58hmybvv {
  cx: 15.276px;
  cy: 23.659px;
  r: 9.25px;
}

.gho3h6r1y {
  d: path("M29.22 27.493a5.05 5.05 0 0 1 7.095.746a5.04 5.04 0 0 1-.746 7.096L17.141 50.261a5.046 5.046 0 0 1-7.098-.744a5.04 5.04 0 0 1 .749-7.096zm4.04 25.204c-2.508-.001-4.535-2.275-4.523-5.063s2.054-5.04 4.565-5.03l21.353.082c2.51.012 4.532 2.278 4.524 5.066c-.012 2.787-2.05 5.04-4.563 5.02l-21.356-.084");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.vcyc_nq8o {
  d: path("M29.6 27.537c.974-1.842 5.313-1.461 9.684.854c4.375 2.315 7.131 5.688 6.157 7.531l-8.309 15.697c-.978 1.846-5.316 1.463-9.692-.852c-4.373-2.317-7.125-5.69-6.149-7.532z");
}

.y49ee0b2y {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M63.921 57.028a6.886 6.886 0 0 1-6.888 6.888H6.89A6.887 6.887 0 0 1 0 57.028V6.888A6.887 6.887 0 0 1 6.89 0h50.144a6.886 6.886 0 0 1 6.888 6.888z");
}

</style>
