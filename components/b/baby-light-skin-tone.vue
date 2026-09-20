<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="z5c0f1nkj"/><path class="wxv211tzw"/><circle class="vfdacephm"/><circle class="j9iq6vb6x"/><path class="ju5-jwd7f"/><path class="lqwh1f2yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:baby-light-skin-tone" /></template>
<style>
.j9iq6vb6x {
  cx: 13.5px;
  cy: 18.5px;
  r: 2.5px;
  fill: var(--svg-color--662113, #662113);
}

.ju5-jwd7f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 26h2v1s0 1-1 1s-1-1-1-1z");
}

.lqwh1f2yp {
  fill: var(--svg-color--d89882, #d89882);
  d: path("M17.982 11h-.031a4.36 4.36 0 0 1-3.135-1.304a3.74 3.74 0 0 1-1.076-2.847a.99.99 0 0 1 1.057-.935c.551.033.972.508.939 1.06c-.029.495.155.983.503 1.336a2.42 2.42 0 0 0 1.725.729c.653-.036 1.27-.247 1.735-.705a3.31 3.31 0 0 0 .032-4.677a4.39 4.39 0 0 0-6.202-.042a.999.999 0 1 1-1.404-1.424a6.395 6.395 0 0 1 9.03.061a5.29 5.29 0 0 1-.052 7.486c-.836.827-1.945 1.262-3.121 1.262");
}

.vfdacephm {
  cx: 22.5px;
  cy: 18.5px;
  r: 2.5px;
  fill: var(--svg-color--662113, #662113);
}

.wxv211tzw {
  fill: var(--svg-color--662113, #662113);
  d: path("M18 25c-3 0-4-1-4 1s2 4 4 4s4-2 4-4s-1-1-4-1");
}

.z5c0f1nkj {
  fill: var(--svg-color--f7dece, #f7dece);
  d: path("M36 18.5c0-1.639-.97-3.004-2.273-3.385C32.367 7.658 25.85 2 18 2S3.633 7.658 2.273 15.115C.97 15.496 0 16.861 0 18.5c0 1.736 1.087 3.168 2.51 3.442C4.269 28.868 10.527 34 18 34s13.731-5.132 15.49-12.058C34.912 21.668 36 20.236 36 18.5");
}

</style>
