<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t19wzj6gf"/><path class="rq2awccda"/><path class="bhqygsqcn"/><path class="w_bj1rb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-algeria" /></template>
<style>
.bhqygsqcn {
  fill: var(--svg-color--d20f34, #d20f34);
  d: path("M20 24c-3.315 0-6-2.685-6-6s2.685-6 6-6c1.31 0 2.52.425 3.507 1.138A7.33 7.33 0 0 0 18 10.647A7.353 7.353 0 0 0 10.647 18A7.353 7.353 0 0 0 18 25.354c2.195 0 4.16-.967 5.507-2.492A5.96 5.96 0 0 1 20 24");
}

.rq2awccda {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H18v26h14a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.t19wzj6gf {
  fill: var(--svg-color--006233, #006233);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h14V5z");
}

.w_bj1rb8i {
  fill: var(--svg-color--d20f34, #d20f34);
  d: path("m25.302 18.23l-2.44.562l-.22 2.493l-1.288-2.146l-2.44.561l1.644-1.888l-1.287-2.147l2.303.98l1.644-1.889l-.22 2.494z");
}

</style>
