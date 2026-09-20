<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yu20kj14u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-exclamation-16-filled" /></template>
<style>
.yu20kj14u {
  fill: currentColor;
  d: path("M12 2.707V14.5a.5.5 0 0 1-1 0V2.707L9.854 3.854a.5.5 0 1 1-.708-.708l2-2a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1-.708.708zM4.5 1A2.5 2.5 0 0 0 2 3.5c0 2.318.67 4.768 1.036 5.938c.203.65.806 1.062 1.464 1.062s1.261-.412 1.464-1.062C6.33 8.268 7 5.818 7 3.5A2.5 2.5 0 0 0 4.5 1M2.75 13.25a1.75 1.75 0 1 1 3.5 0a1.75 1.75 0 0 1-3.5 0");
}

</style>
