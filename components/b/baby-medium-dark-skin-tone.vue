<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fffxcgjtm"/><path class="jjjtkmb5m"/><circle class="w37p1xb4e"/><circle class="fsau0ibwu"/><path class="ju5-jwd7f"/><path class="me_jt2wgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:baby-medium-dark-skin-tone" /></template>
<style>
.fffxcgjtm {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M36 18.5c0-1.639-.97-3.004-2.273-3.385C32.367 7.658 25.85 2 18 2S3.633 7.658 2.273 15.115C.97 15.496 0 16.861 0 18.5c0 1.736 1.087 3.168 2.51 3.442C4.269 28.868 10.527 34 18 34s13.731-5.132 15.49-12.058C34.912 21.668 36 20.236 36 18.5");
}

.fsau0ibwu {
  cx: 13.5px;
  cy: 18.5px;
  r: 2.5px;
  fill: var(--svg-color--662214, #662214);
}

.jjjtkmb5m {
  fill: var(--svg-color--662214, #662214);
  d: path("M18 25c-3 0-4-1-4 1s2 4 4 4s4-2 4-4s-1-1-4-1");
}

.ju5-jwd7f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 26h2v1s0 1-1 1s-1-1-1-1z");
}

.me_jt2wgw {
  fill: var(--svg-color--845636, #845636);
  d: path("M17.982 11h-.031a4.36 4.36 0 0 1-3.135-1.304a3.74 3.74 0 0 1-1.076-2.847a.99.99 0 0 1 1.057-.935c.551.033.972.508.939 1.06c-.029.495.155.983.503 1.336a2.42 2.42 0 0 0 1.725.729c.653-.036 1.27-.247 1.735-.705a3.31 3.31 0 0 0 .032-4.677a4.39 4.39 0 0 0-6.202-.042a.999.999 0 1 1-1.404-1.424a6.394 6.394 0 0 1 9.03.062a5.29 5.29 0 0 1-.052 7.486c-.836.826-1.945 1.261-3.121 1.261");
}

.w37p1xb4e {
  cx: 22.5px;
  cy: 18.5px;
  r: 2.5px;
  fill: var(--svg-color--662214, #662214);
}

</style>
