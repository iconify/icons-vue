<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6ht4b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:display-external-input-sharp" /></template>
<style>
.ju6ht4b4e {
  fill: currentColor;
  d: path("m18 22l-1.425-1.425l1.6-1.575H14v-2h4.175L16.6 15.4L18 14l4 4zM3 21v-6h2v4h4v2zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6z");
}

</style>
