<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k5tevjqrg"/><path class="zi9ptrwqh"/><path class="rhkc3mbjz"/><path class="m1igw580x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cnht" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k5tevjqrg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.631 3.9H6.343L3 11.237l9 8.863l9-8.863z");
}

.m1igw580x {
  fill: var(--svg-color--009f74, #009f74);
  d: path("M11.1 16.5v-4.172h1.8V16.5zm4.95-9.9h-8.1v1.8h3.15v3.15h1.8V8.4h3.15z");
}

.rhkc3mbjz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 12c2.734 0 4.95-.403 4.95-.9s-2.216-.9-4.95-.9s-4.95.403-4.95.9s2.217.9 4.95.9");
}

.zi9ptrwqh {
  fill: var(--svg-color--009f74, #009f74);
  d: path("M12.002 12.45c2.983 0 5.4-.604 5.4-1.35s-2.418-1.35-5.4-1.35s-5.4.604-5.4 1.35s2.418 1.35 5.4 1.35");
}

</style>
