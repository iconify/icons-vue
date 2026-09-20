<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l46n-_bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:jmpt" /></template>
<style>
.l46n-_bpb {
  fill: var(--svg-color--3256f2, #3256f2);
  d: path("M16.737 6.79L14.605 3l-2.131 3.79h.947v10.705a1.421 1.421 0 0 1-2.842 0v-6.916h.947l-2.131-3.79l-2.132 3.79h.948v7.082C8.21 19.508 9.646 21 11.413 21h1.174c1.767 0 3.203-1.497 3.203-3.34V6.79z");
}

</style>
