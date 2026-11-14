<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvb_0bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:co2-tag" /></template>
<style>
.blvb_0bgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 4.25h11q2.75 0 2.75 2.75v10q0 2.75-2.75 2.75h-11q-.164 0-.313-.069q-.15-.068-.256-.193l-6-7q-.044-.05-.078-.108q-.033-.057-.056-.12q-.024-.062-.035-.128q-.012-.065-.012-.132t.012-.132q.011-.066.035-.128q.023-.063.056-.12q.034-.058.078-.108l6-7q.106-.125.256-.193q.149-.069.313-.069M12.25 16h4.5q2.5 0 2.5-2.5q0-2.302-2.12-2.484q-1.008-1.185-2.63-1.185t-2.63 1.185q-2.12.182-2.12 2.484q0 2.5 2.5 2.5");
}

</style>
