<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2hy-cb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barn-owl" /></template>
<style>
.u2hy-cb4n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.903q2.494-2.429 5.605-1.43Q21.25 4.645 21.25 9.5q0 7.714-8.915 12.171q-.078.039-.163.059t-.172.02t-.172-.02t-.163-.059Q2.75 17.214 2.75 9.5q0-4.855 3.645-6.027Q9.506 2.474 12 4.903M5.75 10.5q0 2.75 2.75 2.75t2.75-2.75T8.5 7.75T5.75 10.5m9.75-2.75q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75t-2.75-2.75M12.75 16v-2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 12.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V16q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
