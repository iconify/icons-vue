<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t76_qd-2z"/><path class="n8-91eb0z"/><path class="ffqvh7osi"/><path class="mqzz_4ces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-syria" /></template>
<style>
.ffqvh7osi {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

.mqzz_4ces {
  fill: var(--svg-color--137a08, #137a08);
  d: path("m15.734 26.342l1.768 3.583l3.957.579l-2.862 2.796l.676 3.93l-3.539-1.86l-3.54 1.86l.678-3.93l-2.862-2.796l3.958-.579zm32.213 0l1.768 3.583l3.958.579L50.81 33.3l.68 3.93l-3.543-1.86l-3.537 1.86l.68-3.93l-2.87-2.796l3.96-.579z");
}

.n8-91eb0z {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

.t76_qd-2z {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 25h64v14H0z");
}

</style>
