<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za9uchb8f"/><path class="j2-x-cbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-2-bold-duotone" /></template>
<style>
.j2-x-cbeh {
  fill: currentColor;
  d: path("M2 11C2 7.22876 2 5.34315 3.17157 4.17157C4.34315 3 6.22876 3 10 3H14C17.7712 3 19.6569 3 20.8284 4.17157C22 5.34315 22 7.22876 22 11V13C22 16.7712 22 18.6569 20.8284 19.8284C19.6569 21 17.7712 21 14 21H10C6.22876 21 4.34315 21 3.17157 19.8284C2 18.6569 2 16.7712 2 13V11Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.za9uchb8f {
  fill: currentColor;
  d: path("M11.25 3L12.75 3L12.75 21L11.25 21L11.25 3Z");
}

</style>
