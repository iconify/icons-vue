<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGks2D8dBv)" clip-rule="evenodd" class="qqqa0_gae"/><path class="v0rgsccly"/><path fill="url(#SVGUEZnhcZr)" class="z20_u1o4s"/><defs><linearGradient id="SVGks2D8dBv" x1="3.265" x2="20.735" y1="12.529" y2="12.529" gradientUnits="userSpaceOnUse"><stop class="a-b62bstu"/><stop offset="1" class="rb59ef77z"/></linearGradient><linearGradient id="SVGUEZnhcZr" x1="7.5" x2="15.177" y1="9.618" y2="16.235" gradientUnits="userSpaceOnUse"><stop class="rl5whpb9s"/><stop offset="1" class="ob9j6bdvr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcb" /></template>
<style>
.a-b62bstu {
  stop-color: var(--svg-color--0387fa, #0387fa);
}

.ft5dv1b6b {
  fill: none;
}

.ob9j6bdvr {
  stop-color: var(--svg-color--017ef2, #017ef2);
}

.qqqa0_gae {
  fill-rule: evenodd;
  d: path("M12 19.941a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.rb59ef77z {
  stop-color: var(--svg-color--01feff, #01feff);
}

.rl5whpb9s {
  stop-color: var(--svg-color--11f6fc, #11f6fc);
}

.v0rgsccly {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.942 8.295l-1.06 1.059v2.117l1.854-2.117h1.588l-1.059 1.058h-.53l-1.058 1.06h3.97l-1.058 1.587h-2.647l-1.06 1.06h4.766l2.382-3.707h-2.912l2.118-2.117z");
}

.z20_u1o4s {
  d: path("m7.924 8.342l.9.9v.752l-.688-.688l-1.393 3.954l2.78 3.007l.407-1.09h.567l-.784 2.086l-3.573-3.876l1.778-5.045zm2.63 6.835l-.82 2.192l5.374-.9l.429-1.292h-.556l-.275.826l-4.156.688l.577-1.514z");
}

</style>
