<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zcz9edxis"/><path class="v_raw1b1z"/><path class="wyyf_nxqq"/><path class="xd0eo8asm"/><path class="vukjrlbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cocktail-glass" /></template>
<style>
.v_raw1b1z {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M32 7.442c0-1.622-6.547-2.935-14.623-2.935S2.754 5.82 2.754 7.442c0 .756 1.436 1.443 3.775 1.963c2.746 2.341 7.298 6.098 9.627 8.013c.9.741 2.135.623 2.801.123c.503-.377 6.606-5.643 9.57-8.203C30.69 8.827 32 8.166 32 7.442");
}

.vukjrlbsu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.797 10.761c-3.775 0-7.361-.49-10.737-1.471l-.129-.037a1 1 0 0 1 .555-1.922l.132.039c6.533 1.898 13.942 1.855 22.018-.132a1 1 0 0 1 .479 1.942c-4.289 1.054-8.404 1.581-12.318 1.581");
}

.wyyf_nxqq {
  fill: var(--svg-color--662113, #662113);
  d: path("M16.868 16.532c-.237-.125-.05-.8.248-1.328L24.564.686a1.1 1.1 0 1 1 1.914 1.082l-8.667 13.885c-.15.264-.674 1.02-.943.879");
}

.xd0eo8asm {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M21.745 7.855c1.133.639 1.996 2.636 1.2 4.046c-.797 1.411-2.954 1.699-4.087 1.059s-2.065-2.515-1.199-4.046s2.953-1.699 4.086-1.059");
}

.zcz9edxis {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M19 20.255S30.458 9.214 31.583 8.25S30.875 6 28.626 6H6.129c-1.125 0-4.483.729-2.796 2.417C4.537 9.62 16 20.255 16 20.255v10.123s-4.584 2.34-5.498 2.883c-.984.562-.33 1.462.063 1.617c.656.258 2.253 1.102 6.78 1.102c4.641 0 6.202-.914 6.765-1.102c.217-.072 1.347-.932.011-1.723C21.743 31.747 19 30.378 19 30.378z");
}

</style>
