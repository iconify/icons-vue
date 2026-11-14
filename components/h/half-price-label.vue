<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_4kv0bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:half-price-label" /></template>
<style>
.a_4kv0bks {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.905 3.75h6.97q3.375 0 3.375 3.375v9.75q0 3.375-3.375 3.375h-6.97q-1.806 0-2.808-1.503l-3.25-4.875q-1.248-1.872 0-3.744l3.25-4.875Q8.099 3.75 9.905 3.75M9.25 12q0 1.968 1.391 3.359T14 16.75t3.359-1.391T18.75 12t-1.391-3.359T14 7.25t-3.359 1.391T9.25 12m-1-.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.5 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T9.01 12t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
