<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="kixuz2k3v"><path class="m0k5r_b8y"/><path class="ld_1pwbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:handy" /></template>
<style>
.kixuz2k3v {
  fill: var(--svg-color--ffaa4d, #ffaa4d);
}

.ld_1pwbfq {
  d: path("M10.886 14.813a2.802 2.802 0 0 0 1.975-4.804a2.8 2.8 0 0 0-1.986-.822zM8.062 3C6.51 3 5.25 4.153 5.25 5.57v12.86c0 1.417 1.26 2.57 2.812 2.57c1.553 0 2.813-1.153 2.813-2.57V5.57c0-1.417-1.26-2.57-2.813-2.57m2.813 6.187l-.011 5.626a2.802 2.802 0 0 1-1.975-4.804a2.8 2.8 0 0 1 1.986-.822");
}

.m0k5r_b8y {
  d: path("M13.125 5.57c0-1.417 1.26-2.57 2.813-2.57c1.552 0 2.812 1.153 2.812 2.57v12.86c0 1.417-1.26 2.57-2.812 2.57c-1.553 0-2.813-1.153-2.813-2.57z");
}

</style>
