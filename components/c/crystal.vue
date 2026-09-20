<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p_6h7qfjs"/><path class="mvouk26yu"/><path class="peqbric8j"/><path class="xvsmtbbso"/><path class="b448g27eu"/><path class="koradnroi"/><path class="scq7dqb_j"/><path fill="url(#SVGorXsxcNd)" class="sdb8vjbfn"/><defs><linearGradient id="SVGorXsxcNd" x1="10.364" x2="15.273" y1="13.636" y2="16.636" gradientUnits="userSpaceOnUse"><stop class="c2ivumu1e"/><stop offset="1" class="pq7hpf5cd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crystal" /></template>
<style>
.b448g27eu {
  fill: var(--svg-color--8ac4de, #8ac4de);
  d: path("M12 10.636V6.818l-2.728 5.454l.819.818l-1.637.819l-1.909 4.636l2.182-1.91z");
}

.c2ivumu1e {
  stop-color: var(--svg-color--d2edfb, #d2edfb);
}

.ft5dv1b6b {
  fill: none;
}

.koradnroi {
  fill: var(--svg-color--58779f, #58779f);
  d: path("M12 10.636V6.818l2.727 5.454l-.818.818l1.636.819l1.91 4.636l-2.183-1.91z");
}

.mvouk26yu {
  fill: var(--svg-color--7e8b92, #7e8b92);
  d: path("M12 6.273V3l8.727 18L18 18.818z");
}

.p_6h7qfjs {
  fill: var(--svg-color--d2e2da, #d2e2da);
  d: path("M12 6.273V3L3.273 21L6 18.818z");
}

.peqbric8j {
  fill: var(--svg-color--5a687a, #5a687a);
  d: path("M18 18.818H6L3.273 21h17.454z");
}

.pq7hpf5cd {
  stop-color: var(--svg-color--91cce5, #91cce5);
}

.scq7dqb_j {
  fill: var(--svg-color--475985, #475985);
  d: path("M15.272 16.637H8.727l-2.182 1.909h4.091l.818-.818h1.091l.818.818h4.09z");
}

.sdb8vjbfn {
  d: path("m8.728 16.636l3.272-6l3.273 6z");
}

.xvsmtbbso {
  fill: var(--svg-color--6a7c8b, #6a7c8b);
  d: path("m6 18.818l6-12.545l6 12.545z");
}

</style>
