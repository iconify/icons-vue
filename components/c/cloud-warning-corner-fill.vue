<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-twz_h3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-warning-corner-fill" /></template>
<style>
.o-twz_h3z {
  fill: currentColor;
  d: path("M7 20a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10H10a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1Zm11-6v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
