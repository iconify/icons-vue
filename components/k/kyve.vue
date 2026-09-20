<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGZujbQeTD)" class="d1xxmvbaw"/><defs><linearGradient id="SVGZujbQeTD" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="kw2himb5s"/><stop offset="1" class="r0x0v5s4j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kyve" /></template>
<style>
.d1xxmvbaw {
  d: path("M3.964 21L7.77 3h3.446l-1.582 7.45h.624L15.992 3h4.044v.347l-6.892 8.486v.399l4.417 8.51V21h-3.844l-3.761-7.45h-.984L7.384 21z");
}

.ft5dv1b6b {
  fill: none;
}

.kw2himb5s {
  stop-color: var(--svg-color--151e1d, #151e1d);
}

.r0x0v5s4j {
  stop-color: var(--svg-color--23584e, #23584e);
}

</style>
