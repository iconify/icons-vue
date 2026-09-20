<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7nm587fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acx" /></template>
<style>
.t7nm587fk {
  fill: var(--svg-color--6cf9d7, #6cf9d7);
  d: path("M9.66 11.466L3 4.806L4.806 3l6.66 6.66a2.4 2.4 0 0 0-1.806 1.806m2.874-1.806a2.4 2.4 0 0 1 1.806 1.806L21 4.806L19.194 3zm1.806 2.874a2.4 2.4 0 0 1-1.806 1.806l6.66 6.66L21 19.194zm-2.874 1.806L4.806 21L3 19.194l6.66-6.66a2.4 2.4 0 0 0 1.806 1.806");
}

</style>
