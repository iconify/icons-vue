<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rkxfp5bew"/><path class="hg0wne_6v"/><path class="rju9-4ojg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-iceland" /></template>
<style>
.hg0wne_6v {
  fill: var(--svg-color--d72828, #d72828);
  d: path("M14.5 5h-2.944l-.025 11.5H0v3h11.525L11.5 31h3V19.5H36v-3H14.5z");
}

.rju9-4ojg {
  fill: var(--svg-color--eee, #eee);
  d: path("M14.5 31H16V21h20v-1.5H14.5zM16 5h-1.5v11.5H36V15H16zm-4.5 0H10v10H0v1.5h11.5zM0 19.5V21h10v10h1.5V19.5z");
}

.rkxfp5bew {
  fill: var(--svg-color--003897, #003897);
  d: path("M10 5H4a4 4 0 0 0-4 4v6h10zm22 0H16v10h20V9a4 4 0 0 0-4-4M10 31H4a4 4 0 0 1-4-4v-6h10zm22 0H16V21h20v6a4 4 0 0 1-4 4");
}

</style>
