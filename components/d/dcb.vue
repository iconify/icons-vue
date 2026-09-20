<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGvXWZOeXV)" class="awm9b4bon"/><defs><linearGradient id="SVGvXWZOeXV" x1="6.556" x2="19.942" y1="17.464" y2="10.189" gradientUnits="userSpaceOnUse"><stop class="zzyp99m5y"/><stop offset="1" class="sgdfn7bki"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dcb" /></template>
<style>
.awm9b4bon {
  d: path("M14.613 5.903c0-2.48 1.405-2.903 2.903-2.903v11.654c0 1.3.058 2.438-.58 3.443c1.16 0 2.322 1.335 2.322 2.903h-8.42c-3.35 0-6.096-2.845-6.096-6.346c0-3.508 2.961-6.428 6.311-6.428c1.243 0 2.602.493 3.56 1.161zm-3.56 12.194c1.858 0 3.56-1.51 3.56-3.443a3.594 3.594 0 0 0-3.525-3.525a3.483 3.483 0 0 0-3.443 3.484c0 1.94 1.556 3.484 3.408 3.484");
}

.ft5dv1b6b {
  fill: none;
}

.sgdfn7bki {
  stop-color: var(--svg-color--4d0e75, #4d0e75);
}

.zzyp99m5y {
  stop-color: var(--svg-color--c41859, #c41859);
}

</style>
