<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vnv6z1bwi"/><path clip-rule="evenodd" class="mahbf_r9f"/><path clip-rule="evenodd" class="mr7g-ob5n"/><path clip-rule="evenodd" class="zr5yvwmve"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clipboard-check-circled-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.mahbf_r9f {
  fill-rule: evenodd;
  d: path("M8 19V8h1V6H7a1 1 0 0 0-1 1v13a1 1 0 0 0 1 1h6.337a5.5 5.5 0 0 1-1.737-2zm10-7.793c.742.21 1.421.572 2 1.05V7a1 1 0 0 0-1-1h-2v2h1z");
}

.mr7g-ob5n {
  fill-rule: evenodd;
  d: path("M16.5 20a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0 2a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.vnv6z1bwi {
  fill-rule: evenodd;
  d: path("M8.68 5.5a1 1 0 0 1 1-1h6.643a1 1 0 0 1 1 1v3.875a1 1 0 0 1-1 1H9.68a1 1 0 0 1-1-1zm2 1v1.875h4.643V6.5z");
}

.zr5yvwmve {
  fill-rule: evenodd;
  d: path("M18.87 14.72a1 1 0 0 1 .156 1.405l-1.65 2.063a1.5 1.5 0 0 1-2.233.124l-1.104-1.105a1 1 0 0 1 1.414-1.414l.71.71l1.302-1.628a1 1 0 0 1 1.405-.156");
}

</style>
