<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="voplmqbhj"/><path class="q0860fblg"/><path class="mwkjxmcfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-bosnia-and-herzegovina" /></template>
<style>
.mwkjxmcfi {
  fill: var(--svg-color--fbd116, #FBD116);
  d: path("M28 31V5H11z");
}

.q0860fblg {
  fill: var(--svg-color--e1e8ed, #E1E8ED);
  d: path("M6.965 6.607l.956-.695l.955.695l-.364-1.123L9.177 5H6.665l.665.484zm19.002 23.374h-1.181l-.365-1.122l-.365 1.122h-1.181l.955.695l-.105.324h1.392l-.106-.324zM9.999 6.815l.364 1.123h1.182l-.956.695l.365 1.123l-.955-.695l-.956.695l.365-1.123l-.955-.695h1.18zm2.069 3.15l.365 1.122h1.182l-.956.695l.365 1.123l-.956-.694l-.955.694l.365-1.123l-.956-.695h1.181zm2.054 3.148l.365 1.123h1.181l-.956.695l.365 1.123l-.955-.695l-.956.695l.365-1.123l-.955-.695h1.181zm2.061 3.15l.365 1.123h1.181l-.955.694l.365 1.123l-.956-.694l-.955.694l.365-1.123l-.956-.694h1.181zm2.061 3.149l.365 1.123h1.182l-.956.694l.365 1.124l-.956-.695l-.955.695l.365-1.124l-.955-.694h1.181zm2.062 3.149l.365 1.123h1.181l-.955.694l.364 1.123l-.955-.694l-.955.694l.364-1.123l-.955-.694h1.181zm2.053 3.148l.365 1.124h1.182l-.956.694l.365 1.123l-.956-.694l-.955.694l.365-1.123l-.956-.694h1.181z");
}

.voplmqbhj {
  fill: var(--svg-color--2d3189, #2D3189);
  d: path("M32 5H9.177l-.665.484l.365 1.123l-.956-.695l-.956.695l.365-1.123L6.665 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h19.725l.105-.324l-.955-.695h1.181l.365-1.123l.365 1.123h1.181l-.955.695l.105.324H32a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

</style>
