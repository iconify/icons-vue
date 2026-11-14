<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1qqfcb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aisle-wheelchair" /></template>
<style>
.s1qqfcb0e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 3.25h3.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T7.25 4v4.983Q8.077 8.75 9 8.75q2.589 0 4.419 1.831q.768.768 1.214 1.669H16q.095 0 .187.024q.092.023.175.069t.152.111t.12.146l2.792 4.42q2.074.203 2.074 2.48q0 2.5-2.5 2.5t-2.5-2.5q0-1.782 1.27-2.294l-2.183-3.456h-.452q.115.601.115 1.25q0 2.589-1.831 4.419Q11.589 21.25 9 21.25t-4.419-1.831Q2.75 17.589 2.75 15t1.831-4.419q.55-.551 1.169-.936V4.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 4.074 2.25 4t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q2.926 3.25 3 3.25");
}

</style>
