<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":243};
const content = `<path class="ugggrvbpi"/><path class="g8u66cbvc"/><path class="n4qfu3b1j"/><path class="urd8rjbti"/><path class="fl4b_1b4b"/><path class="i3nxq9b4d"/><path class="fd4no41bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lexical-icon" /></template>
<style>
.fd4no41bd {
  d: path("M236.475 0v21.695H212.61v199.593h23.865v21.695H169.22v-21.695h21.695V21.695H169.22V0zm-56.407 32.542v21.695H21.695v134.509h158.373v21.695H0V32.542zm75.932 0v177.899h-32.542v-21.695h10.847V54.237h-10.847V32.542z");
}

.fl4b_1b4b {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M101.966 145.356h47.729v21.695h-47.729z");
}

.g8u66cbvc {
  d: path("M101.966 75.932h47.729v21.695h-47.729z");
}

.i3nxq9b4d {
  d: path("M160.542 145.356h19.526v21.695h-19.526z");
}

.n4qfu3b1j {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M160.542 75.932h19.526v21.695h-19.526zM43.39 110.644h78.102v21.695H43.39zm88.949 0h47.729v21.695h-47.729z");
}

.ugggrvbpi {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M43.39 75.932h47.729v21.695H43.39z");
}

.urd8rjbti {
  d: path("M43.39 145.356h47.729v21.695H43.39z");
}

</style>
