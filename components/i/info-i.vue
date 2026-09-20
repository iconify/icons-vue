<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm5azwboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:info-i" /></template>
<style>
.gm5azwboa {
  fill: currentColor;
  d: path("M10.934 6.566Q10.5 6.133 10.5 5.5t.434-1.066Q11.367 4 12 4t1.066.434T13.5 5.5t-.434 1.066Q12.633 7 12 7t-1.066-.434M11 20V9.77h2V20z");
}

</style>
