<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGuNZ8N5dZ)" class="yjc9_0bfb"/><path fill="url(#SVGZKSZSFJh)" clip-rule="evenodd" class="xmvgoac6j"/><defs><linearGradient id="SVGuNZ8N5dZ" x1="12.001" x2="12.001" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="zui8q7bhp"/><stop offset="1" class="c2ap7hb9w"/></linearGradient><linearGradient id="SVGZKSZSFJh" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="zui8q7bhp"/><stop offset="1" class="c2ap7hb9w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:key" /></template>
<style>
.c2ap7hb9w {
  stop-color: var(--svg-color--58b9cf, #58b9cf);
}

.ft5dv1b6b {
  fill: none;
}

.xmvgoac6j {
  fill-rule: evenodd;
  d: path("M12 3L4 7.485v8.99L12 21l8-4.525v-8.99zm2.045 3.5H11.54c-.19.005-.53.14-.54.615v6.448a2 2 0 1 0 1 0V9.5h1.58c.15 0 .42-.17.42-.5c0-.325-.265-.5-.42-.5H12v-1h2.05c.175 0 .45-.195.45-.5a.48.48 0 0 0-.455-.5");
}

.yjc9_0bfb {
  d: path("M11.5 16.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.zui8q7bhp {
  stop-color: var(--svg-color--4ab0e1, #4ab0e1);
}

</style>
