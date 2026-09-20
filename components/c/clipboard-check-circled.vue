<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vcoctpbrs"/><path class="sd9ds6b4c"/><path class="t5kbw-puj"/><path class="j4z1iztxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clipboard-check-circled" /></template>
<style>
.j4z1iztxe {
  d: path("M15.87 11.72a1 1 0 0 1 .156 1.405l-1.65 2.063a1.5 1.5 0 0 1-2.232.124l-1.105-1.105a1 1 0 0 1 1.414-1.414l.71.71l1.302-1.628a1 1 0 0 1 1.405-.156");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.sd9ds6b4c {
  d: path("M5 16V5h1V3H4a1 1 0 0 0-1 1v13a1 1 0 0 0 1 1h6.337A5.5 5.5 0 0 1 8.6 16zm10-7.793c.742.21 1.421.572 2 1.05V4a1 1 0 0 0-1-1h-2v2h1z");
}

.t5kbw-puj {
  d: path("M13.5 17a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0 2a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.vcoctpbrs {
  d: path("M5.68 2.5a1 1 0 0 1 1-1h6.643a1 1 0 0 1 1 1v3.875a1 1 0 0 1-1 1H6.68a1 1 0 0 1-1-1zm2 1v1.875h4.643V3.5z");
}

</style>
