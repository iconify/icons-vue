<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="neke5dbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-28-regular" /></template>
<style>
.neke5dbhe {
  fill: currentColor;
  d: path("M24.954 20c1.13 0 2.046.915 2.046 2.045v.205c0 1.868-1.572 3.75-5.5 3.75S16 24.125 16 22.25v-.205c0-1.13.916-2.045 2.046-2.045zM12.234 2.842a3.75 3.75 0 0 1 3.53 0l9.242 4.907a1.25 1.25 0 0 1-.017 2.216l-10.651 5.453a.75.75 0 0 1-.684 0l-10.13-5.19a2 2 0 0 0-.024.322v8.7a2.25 2.25 0 0 0 2.25 2.25h9.3q-.049.266-.05.545v.205q0 .377.067.75H5.75A3.75 3.75 0 0 1 2 19.25v-8.7a3.75 3.75 0 0 1 1.985-3.31zM21.5 13a3 3 0 1 1 0 6a3 3 0 0 1 0-6m-6.442-8.835a2.25 2.25 0 0 0-2.118 0l-8.249 4.4a2.3 2.3 0 0 0-.471.335l9.776 5.007l9.882-5.06z");
}

</style>
