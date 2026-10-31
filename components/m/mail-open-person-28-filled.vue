<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ztr6udbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-28-filled" /></template>
<style>
.ztr6udbqy {
  fill: currentColor;
  d: path("M24.954 20c1.13 0 2.046.915 2.046 2.045v.205c0 1.868-1.572 3.75-5.5 3.75S16 24.125 16 22.25v-.205c0-1.13.916-2.045 2.046-2.045zm-11.3-4.581c.214.11.47.11.684 0l4.283-2.194A4 4 0 0 0 17.5 16c0 1.195.524 2.267 1.355 3h-.81A3.045 3.045 0 0 0 15 22.045v.205q0 .377.067.75H5.75A3.75 3.75 0 0 1 2 19.25v-8.7q.002-.531.144-1.028zM21.5 13a3 3 0 1 1 0 6a3 3 0 0 1 0-6M12.233 2.842a3.75 3.75 0 0 1 3.53 0l8.249 4.4c.45.24.838.564 1.148.947l-11.164 5.72L2.835 8.19c.31-.384.7-.71 1.15-.95z");
}

</style>
