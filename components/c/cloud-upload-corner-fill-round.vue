<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3z7m-xyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-upload-corner-fill-round" /></template>
<style>
.g3z7m-xyw {
  fill: currentColor;
  d: path("M17.791 10H12a3 3 0 0 0-3 3v6a1 1 0 0 1-1 1H7a6 6 0 0 1-.74-11.955c.742-2.012 2.206-3.704 4.274-4.403c2.856-.964 5.823.266 7.337 2.833c.419.717.721 1.496.896 2.307A.998.998 0 0 1 17.791 10m1.502 6.707L18 15.414V21a1 1 0 0 1-2 0v-5.586l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414");
}

</style>
