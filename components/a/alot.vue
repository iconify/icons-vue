<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGE1lRBblo)" class="h8gpv41mt"/><defs><linearGradient id="SVGE1lRBblo" x1="6.894" x2="18.035" y1="16.019" y2="4.183" gradientUnits="userSpaceOnUse"><stop class="ea17l_-qp"/><stop offset="1" class="edza-vyle"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alot" /></template>
<style>
.ea17l_-qp {
  stop-color: var(--svg-color--eb1357, #eb1357);
}

.edza-vyle {
  stop-color: var(--svg-color--db23c8, #db23c8);
}

.ft5dv1b6b {
  fill: none;
}

.h8gpv41mt {
  d: path("m21 9.79l-4.07 2.67c3.21-2.6 3.21-5.413 3.21-5.413l-4.254 4.268c2.864-4.823 1.815-6.813 1.815-6.813l-3.39 5.814a8.4 8.4 0 0 0-2.278-.31h-.056c-.77 0-1.534.1-2.279.31L6.304 4.502S5.114 6.327 7.98 11.15L3.87 7.052s-.42 2.489 3.01 5.253C6.86 12.335 3 9.79 3 9.79s-.1 2.4 3.3 4.318v.065c0 2.6 2.533 5.299 5.677 5.324h.05c3.14-.03 5.679-2.72 5.679-5.324v-.065C21.1 12.19 21 9.791 21 9.791M10.083 16.79s-1.005.07-1.584-.54c-.58-.605-.51-1.66-.51-1.66s1.01-.07 1.59.54s.504 1.665.504 1.665zm5.428-.54c-.58.61-1.584.545-1.584.545s-.065-1.055.515-1.665s1.584-.54 1.584-.54s.06 1.05-.525 1.66z");
}

</style>
