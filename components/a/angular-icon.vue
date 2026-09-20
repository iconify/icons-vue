<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":271};
const content = `<defs><linearGradient id="SVGpqdn3GZR" x1="25.071%" x2="96.132%" y1="90.929%" y2="55.184%"><stop offset="0%" class="ihp9v4bld"/><stop offset="24%" class="s_y3ovbsy"/><stop offset="35.2%" class="u6k56-beg"/><stop offset="49.4%" class="dwc4u9pmz"/><stop offset="74.5%" class="m3um371oc"/><stop offset="100%" class="ogd4x_olp"/></linearGradient><linearGradient id="SVGVcJbhdIj" x1="21.863%" x2="68.367%" y1="12.058%" y2="68.21%"><stop offset="0%" class="ja-uenb8g"/><stop offset="100%" class="pocirabxc"/></linearGradient></defs><path fill="url(#SVGpqdn3GZR)" class="a_w5tebcy"/><path fill="url(#SVGVcJbhdIj)" class="a_w5tebcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:angular-icon" /></template>
<style>
.a_w5tebcy {
  d: path("m256 45.179l-9.244 145.158L158.373 0zm-61.217 187.697l-66.782 38.105l-66.784-38.105L74.8 199.958h106.4zM128.001 72.249l34.994 85.076h-69.99zM9.149 190.337L0 45.179L97.627 0z");
}

.dwc4u9pmz {
  stop-color: var(--svg-color--dc087d, #dc087d);
}

.ihp9v4bld {
  stop-color: var(--svg-color--e40035, #e40035);
}

.ja-uenb8g {
  stop-color: var(--svg-color--ff31d9, #ff31d9);
}

.m3um371oc {
  stop-color: var(--svg-color--9717e7, #9717e7);
}

.ogd4x_olp {
  stop-color: var(--svg-color--6c00f5, #6c00f5);
}

.pocirabxc {
  stop-color: var(--svg-color--ff5be1, #ff5be1);
  stop-opacity: 0;
}

.s_y3ovbsy {
  stop-color: var(--svg-color--f60a48, #f60a48);
}

.u6k56-beg {
  stop-color: var(--svg-color--f20755, #f20755);
}

</style>
