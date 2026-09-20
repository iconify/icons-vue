<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qq65xxbeb"/><path class="ky0ybmb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gtc" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.ky0ybmb4t {
  fill: var(--svg-color--0e0333, #0e0333);
  d: path("M9.285 3.53a.53.53 0 1 1 1.06 0v2.038a8 8 0 0 1 1.587-.382V3.53a.529.529 0 1 1 1.06 0v1.587a7.9 7.9 0 0 1 5.932 2.664l.028.032l-4.203 3.721a2.385 2.385 0 0 1-.156 2.742l4.221 3.268V21H12.99A7.942 7.942 0 0 1 9.285 6.032zm4.165 11.534a2.382 2.382 0 1 1 .306-4.42l3.232-2.861A6.6 6.6 0 0 0 12.99 6.44c-.941 0-1.836.196-2.646.55v2.363a.529.529 0 1 1-1.059 0v-1.78a6.61 6.61 0 0 0-2.914 5.485a6.62 6.62 0 0 0 6.73 6.617h4.388v-1.483zm.335-2.27a1.059 1.059 0 1 1-2.117 0a1.059 1.059 0 0 1 2.117 0");
}

.qq65xxbeb {
  fill: var(--svg-color--02e2ac, #02e2ac);
  d: path("M17.232 12.756a4.1 4.1 0 0 0-1.514-3.182l1.002-1.232a5.68 5.68 0 0 1 2.1 4.414a5.68 5.68 0 0 1-2.1 4.414l-1.003-1.232a4.1 4.1 0 0 0 1.515-3.182");
}

</style>
