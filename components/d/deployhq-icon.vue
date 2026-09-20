<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":320};
const content = `<path class="um_b2eblg"/><path class="n-1vubchc"/><path class="d7cc-hb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:deployhq-icon" /></template>
<style>
.d7cc-hb1d {
  fill: var(--svg-color--40cf9f, #40cf9f);
  d: path("M192 255.642h64l-64-63.905zM128 0l64 63.905H64zm0 255.644H64.001V127.832H128z");
}

.n-1vubchc {
  d: path("M192 319.529H64l64-63.907zM64 95.858c0 17.648 14.326 31.953 32 31.953c17.673 0 32-14.305 32-31.953c0-17.647-14.327-31.952-32-31.952S64 78.21 64 95.858");
}

.um_b2eblg {
  fill: var(--svg-color--4b25bb, #4b25bb);
  d: path("M64 255.642v-63.905L0 255.642zm127.999-.001h-64V63.924h64z");
}

</style>
