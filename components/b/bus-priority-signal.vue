<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec7podb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bus-priority-signal" /></template>
<style>
.ec7podb-o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.125 1.25h-.25q-2.123 0-3.624 1.501T2.75 6.375v11.25q0 2.123 1.501 3.624t3.624 1.501h.25q2.123 0 3.624-1.501t1.501-3.624V6.375q0-2.123-1.501-3.624T8.125 1.25m-2.375 5Q5.75 4 8 4t2.25 2.25T8 8.5T5.75 6.25m13 .5H16q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v9q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.25q3 0 3-3q0-1.767-1.041-2.493q.541-.733.541-2.007q0-3-3-3M8 9.75q2.25 0 2.25 2.25T8 14.25T5.75 12T8 9.75m-2.25 8q0-2.25 2.25-2.25t2.25 2.25T8 20t-2.25-2.25");
}

</style>
