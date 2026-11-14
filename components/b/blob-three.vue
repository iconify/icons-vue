<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyo5nwbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blob-three" /></template>
<style>
.oyo5nwbxo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.021 12.875q1.313-2.569 3.953-3.208q-.811-2.626.766-5.084Q8.585 1.709 12 1.709t5.26 2.874q1.577 2.458.766 5.084q2.64.639 3.953 3.208q1.539 3.01-.139 5.945t-5.051 3.137q-2.894.174-4.789-1.796q-1.895 1.97-4.789 1.796q-3.374-.202-5.051-3.137t-.139-5.945");
}

</style>
