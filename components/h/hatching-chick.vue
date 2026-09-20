<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jhdleebqh"/><path class="alj12c3bt"/><path class="rc315s9no"/><circle class="zxd8mmban"/><circle class="x3xatnrcb"/><path class="n3ild65kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hatching-chick" /></template>
<style>
.alj12c3bt {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M29.956 14.712c.021-.287.044-.574.044-.866c0-5.943-4.324-10.864-9.996-11.819c1.189-.26 2.031-.509.996-1.027c-1.115-.558-2.23.129-2.999.846h-.002C17.23 1.129 16.116.442 15 1c-1.035.518-.193.767.996 1.026C10.325 2.981 6 7.902 6 13.846c0 .292.023.579.044.867C5.562 21.313-.259 31 18 31s12.438-9.687 11.956-16.288");
}

.jhdleebqh {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M2.75 19.333L5 16l3 3l4-2l3 3l4-6l4 3l3-1l2 3l3-3l2 4l-2 7l-11 5l-11-2l-6-6z");
}

.n3ild65kf {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("m31 25l-3-1l-4 6l-3-5l-2 2l-4-2l-3 4l-3-6l-3 2l-3.294-7.765A13.3 13.3 0 0 0 2 21.5C2 29.509 9.164 36 18 36s16-6.491 16-14.5c0-1.244-.191-2.444-.517-3.597z");
}

.rc315s9no {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M21 14c0 1.657-1.343 2-3 2s-3-.343-3-2a3 3 0 1 1 6 0");
}

.x3xatnrcb {
  cx: 24.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: var(--svg-color--662113, #662113);
}

.zxd8mmban {
  cx: 11.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: var(--svg-color--662113, #662113);
}

</style>
