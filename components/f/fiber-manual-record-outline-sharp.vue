<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi036ub4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fiber-manual-record-outline-sharp" /></template>
<style>
.wi036ub4o {
  fill: currentColor;
  d: path("M7.752 16.248Q6 14.496 6 12t1.752-4.248T12 6t4.248 1.752T18 12t-1.752 4.248T12 18t-4.248-1.752m7.786-.71Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
