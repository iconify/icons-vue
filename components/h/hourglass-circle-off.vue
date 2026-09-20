<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fqaf-zijl"/><path clip-rule="evenodd" class="a1mo55oec"/><path class="a_8_-56vs"/><path clip-rule="evenodd" class="jg0x75bdh"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:hourglass-circle-off" /></template>
<style>
.a_8_-56vs {
  d: path("M10 18.75s2-1.5 3-1.5s3 1.5 3 1.5v.5h-6z");
}

.a1mo55oec {
  fill-rule: evenodd;
  d: path("M15.797 19c-.13-.819-.323-1.595-.575-2.084c-.198-.384-.586-.875-1.118-1.407A16 16 0 0 0 13 14.513c-.352.29-.74.631-1.104.996c-.532.532-.92 1.023-1.118 1.407c-.252.489-.444 1.265-.575 2.084zm.662 2c.844 0 1.518-.697 1.42-1.535c-.125-1.077-.378-2.492-.879-3.465c-.672-1.305-2.218-2.643-3.18-3.393a1.326 1.326 0 0 0-1.64 0c-.962.75-2.508 2.088-3.18 3.393c-.501.973-.754 2.388-.88 3.465c-.097.838.577 1.535 1.421 1.535z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fqaf-zijl {
  fill-rule: evenodd;
  d: path("M10.203 7c.13.819.323 1.595.575 2.084c.198.385.586.874 1.118 1.407c.365.365.752.706 1.104.996c.352-.29.74-.631 1.104-.996c.532-.533.92-1.022 1.118-1.407c.252-.489.444-1.265.575-2.084zm-.662-2c-.844 0-1.518.697-1.42 1.536c.125 1.076.378 2.49.879 3.464c.672 1.305 2.218 2.643 3.18 3.393c.485.38 1.155.38 1.64 0c.962-.75 2.508-2.088 3.18-3.393c.501-.973.754-2.388.88-3.464c.097-.84-.577-1.536-1.421-1.536z");
}

.jg0x75bdh {
  fill-rule: evenodd;
  d: path("M7 5.5a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1m0 15a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
