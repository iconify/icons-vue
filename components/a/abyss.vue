<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGI1g04dgF)" class="grjqo44_v"/><path fill="url(#SVGwMY8t8Vq)" class="e4ph34bjd"/><defs><linearGradient id="SVGI1g04dgF" x1="6.496" x2="18.731" y1="6.106" y2="16.484" gradientUnits="userSpaceOnUse"><stop class="b9y6fwb_x"/><stop offset="1" class="h8oe5jbbu"/></linearGradient><linearGradient id="SVGwMY8t8Vq" x1="6.496" x2="18.731" y1="6.105" y2="16.483" gradientUnits="userSpaceOnUse"><stop class="b9y6fwb_x"/><stop offset="1" class="h8oe5jbbu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abyss" /></template>
<style>
.b9y6fwb_x {
  stop-color: var(--svg-color--a025f3, #a025f3);
}

.e4ph34bjd {
  d: path("M12 3C8.54 3 4.42 4.778 4.42 4.778V15.6L12 21l7.579-5.378V4.755c.022 0-4.1-1.755-7.58-1.755m4.263 11.436l-1.895 1.383v-2.872H9.631v2.871l-1.894-1.382V7.26s2.5-.57 4.285-.57c1.784-.001 4.241.57 4.241.57z");
}

.ft5dv1b6b {
  fill: none;
}

.grjqo44_v {
  d: path("M12.01 8.685c-1.35 0-2.379.208-2.379.208v2.16h4.737V8.894c.022 0-1.007-.21-2.358-.21");
}

.h8oe5jbbu {
  stop-color: var(--svg-color--4212a0, #4212a0);
}

</style>
