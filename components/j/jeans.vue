<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fi1y-8-fq"/><path class="ehthxc7dn"/><path class="yis_d5b2x"/><path class="prnm9ib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:jeans" /></template>
<style>
.ehthxc7dn {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M15.818 0H26v4.568l6.182 29.114L24.454 36l-6.409-23.182z");
}

.fi1y-8-fq {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M20.182 0H10v4.568L3.818 33.682L11.545 36l6.41-23.182z");
}

.prnm9ib6o {
  fill: var(--svg-color--269, #269);
  d: path("M12 0h2v3h-2zm10 0h2v3h-2zm-6 4h2v7h-2z");
}

.yis_d5b2x {
  fill: var(--svg-color--269, #269);
  d: path("M10 2h16v2H10zm9 10h-2l-4-2h10z");
}

</style>
