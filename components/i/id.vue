<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="r27-eqotr"><path clip-rule="evenodd" class="yyxfn9bpz"/><path class="tor6ybcyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:id" /></template>
<style>
.r27-eqotr {
  fill: var(--svg-color--1aed9e, #1aed9e);
}

.tor6ybcyk {
  d: path("M13.125 10.043c0-.788.636-1.418 1.418-1.418h.54c.787 0 1.417.636 1.417 1.418v.54c0 .787-.636 1.417-1.417 1.417h-.54a1.42 1.42 0 0 1-1.418-1.418zm0 5.062c0-.788.636-1.418 1.418-1.418h.54c.787 0 1.417.636 1.417 1.418v.54c0 .788-.636 1.418-1.417 1.418h-.54a1.416 1.416 0 0 1-1.418-1.418z");
}

.yyxfn9bpz {
  fill-rule: evenodd;
  d: path("M8.873 3a5.355 5.355 0 0 0-5.31 5.4v7.2c0 2.981 2.373 5.4 5.31 5.4h6.255c2.936 0 5.31-2.419 5.31-5.4V8.4c0-2.981-2.374-5.4-5.31-5.4zm-.034 2.25c-1.67 0-3.026 1.446-3.026 3.234v7.032c0 1.788 1.355 3.234 3.026 3.234h6.322c1.671 0 3.027-1.446 3.027-3.234V8.484c0-1.788-1.356-3.234-3.027-3.234z");
}

</style>
