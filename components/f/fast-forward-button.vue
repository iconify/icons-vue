<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n35z9t7ub"/><path class="tokt9w6ns"/><path class="j-g6wz47h"/><path class="by2ufnlua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:fast-forward-button" /></template>
<style>
.by2ufnlua {
  fill: var(--svg-color--fff, #fff);
  d: path("m106.9 66.14l-39.8 25.7c-.35.24-.78.34-1.2.3a.63.63 0 0 1-.4-.1c-.1 0-.2-.1-.4-.2c-.24-.11-.45-.28-.6-.5c-.12-.1-.2-.24-.2-.4c-.2-.33-.31-.71-.3-1.1v-22.4l-3 2l-34 22.4c-.35.24-.78.34-1.2.3a.63.63 0 0 1-.4-.1c-.1 0-.2-.1-.4-.2c-.7-.46-1.12-1.26-1.1-2.1v-51.3c-.08-1 .54-1.91 1.5-2.2c.1 0 .2-.1.4-.1c.42-.04.85.06 1.2.3l34 22.4l3 2v-22.4c0-.42.11-.83.3-1.2c.1-.1.1-.2.2-.4c.17-.2.38-.36.6-.5c.1-.1.2-.1.4-.2s.3-.1.4-.1c.42-.04.85.06 1.2.3l39.8 25.8c1.1.76 1.38 2.28.62 3.38c-.17.24-.38.45-.62.62");
}

.j-g6wz47h {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 13.04c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n35z9t7ub {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4.14H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.tokt9w6ns {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4.14H11.5a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.64c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
