<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mv26jwbmj"/><path class="uqg0s5bvj"/><path class="hds85w8go"/><g class="pclzssrrw"><path class="i5fs_4bqi"/><path class="kyw7g9jyl"/><path class="gi_9o1qll"/></g><path class="q0abluxhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:fountain-pen" /></template>
<style>
.gi_9o1qll {
  d: path("M48 12.03c2.083 1.657 4.683 1.866 5.801.464l4.416-5.547c1.118-1.406.334-3.89-1.747-5.551S51.785-.47 50.667.936l-4.416 5.547c-1.116 1.402-.336 3.886 1.749 5.547");
}

.hds85w8go {
  fill: var(--svg-color--59595c, #59595c);
  d: path("m14.1 45.548l8.815 7.02l32.06-36.09l-12.89-10.259z");
}

.i5fs_4bqi {
  d: path("m20.2 50.4l2.715 2.17l32.06-36.09l-4.74-3.779zm-3.39-2.692l-2.71-2.16l27.99-39.33l4.756 3.783z");
}

.kyw7g9jyl {
  d: path("M42.23 4.38c-1.472 1.845-1.111 4.588.806 6.113l7.566 6.03c1.917 1.525 4.672 1.265 6.147-.584c1.473-1.849 1.108-4.588-.81-6.113l-7.57-6.03c-1.917-1.529-4.665-1.27-6.139.584");
}

.mv26jwbmj {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M10.202 46.47c-2.41 3.02-6.306 13.744-2.808 16.534c3.506 2.787 13.08-3.408 15.49-6.433c2.403-3.02-.208-5.01-3.71-7.792c-3.506-2.795-6.57-5.326-8.972-2.309m2.807 3.408c1.123-1.401 2.556-.226 4.192 1.078c1.632 1.3 2.846 2.232 1.73 3.639c-1.121 1.41-5.59 4.303-7.226 2.999c-1.631-1.3.188-6.306 1.304-7.716");
}

.pclzssrrw {
  fill: var(--svg-color--424143, #424143);
}

.q0abluxhg {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M29.872 18.989a2.06 2.06 0 0 0 .332 2.897l12.372 9.85a2.057 2.057 0 1 0 2.563-3.217L32.77 18.665a2.06 2.06 0 0 0-2.898.324");
}

.uqg0s5bvj {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M22.21 51.38c1.63 1.636 2.269 3.187.671 5.193c-2.407 3.02-11.984 9.22-15.49 6.433c-.528-.426-.869-1.043-1.091-1.776c6.401-1.793 14.182-4.401 15.91-9.85");
}

</style>
