<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nlhfwhb-n"><path clip-rule="evenodd" class="fung1sb5r"/><path class="b5i5zexix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fantom" /></template>
<style>
.b5i5zexix {
  d: path("M4.35 18.835V16.05h.9v2.34l2.25 1.16v1zm15.3-13.67V7.95h-.9V5.61L16.5 4.45v-1z");
}

.fung1sb5r {
  fill-rule: evenodd;
  d: path("M11.97 3L6.602 6.046v11.817L11.97 21l5.432-3.137V6.046zm.032.9L7.95 6.33L12 8.692l4.05-2.362zM7.5 7.05v4.05l3.6-2.016zm4.951 2.924v4.05l3.6-2.015zm4.05-2.924v4.05l-3.6-2.016zm-4.95 2.923v4.05L7.95 12.009zm-4.05 2.73v4.698l4.5 2.698l4.5-2.7v-4.698l-4.5 2.448z");
}

.nlhfwhb-n {
  fill: var(--svg-color--26b6ea, #26b6ea);
}

</style>
