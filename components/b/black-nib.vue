<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i933uw4-c"/><path class="fedg9y-6j"/><path class="qr_i84bmn"/><g class="pclzssrrw"><path class="x54lzzb7i"/><path class="yo0bnpbcw"/><path class="xgo_1lbwp"/></g><path class="u9160ggfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:black-nib" /></template>
<style>
.fedg9y-6j {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M40.657 51.663c-1.638 1.643-2.279 3.199-.676 5.214c2.417 3.036 12.03 9.255 15.552 6.458c.53-.428.873-1.048 1.095-1.783c-6.426-1.801-14.238-4.418-15.971-9.889");
}

.i933uw4-c {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M43.707 49.05c-3.516 2.798-6.137 4.795-3.726 7.823c2.417 3.036 12.03 9.255 15.552 6.458c3.512-2.802-.397-13.562-2.818-16.6c-2.412-3.03-5.487-.487-9.01 2.319m7.498 8.849c-1.643 1.309-6.129-1.596-7.254-3.01c-1.121-1.412.099-2.349 1.736-3.653c1.643-1.309 3.084-2.489 4.209-1.082c1.121 1.416 2.947 6.442 1.309 7.746");
}

.pclzssrrw {
  fill: var(--svg-color--424143, #424143);
}

.qr_i84bmn {
  fill: var(--svg-color--59595c, #59595c);
  d: path("m7.762 16.625l12.935-10.3l28.1 39.487l-8.849 7.05z");
}

.u9160ggfe {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M32.969 19.15a2.07 2.07 0 0 1-.333 2.908l-12.422 9.889a2.06 2.06 0 0 1-2.903-.325a2.066 2.066 0 0 1 .33-2.904l12.419-9.893a2.067 2.067 0 0 1 2.909.325");
}

.x54lzzb7i {
  d: path("m7.762 16.625l4.762-3.794l30.16 37.857l-2.727 2.172zm12.935-10.3l-4.768 3.798l30.15 37.857l2.721-2.168z");
}

.xgo_1lbwp {
  d: path("M14.768 12.159c-2.09 1.664-4.7 1.873-5.824.466L4.511 7.057c-1.123-1.412-.335-3.905 1.753-5.573s4.703-1.874 5.826-.463l4.433 5.569c1.121 1.408.337 3.901-1.755 5.569");
}

.yo0bnpbcw {
  d: path("M20.565 4.482c1.478 1.852 1.115 4.606-.809 6.137l-7.596 6.05c-1.924 1.531-4.688 1.271-6.173-.586c-1.477-1.856-1.111-4.606.814-6.138l7.6-6.05c1.927-1.535 4.683-1.274 6.164.587");
}

</style>
