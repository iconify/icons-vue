<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pprgho40c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:log-press" /></template>
<style>
.pprgho40c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 10H8.546q.704 1.306.704 3.75t-.704 3.75H18q.594 0 1.112-.932q.638-1.148.638-2.818Q19.75 10 18 10zm3.5-1.5h1.25V5.75q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T15.5 5h2.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.898q2.25.734 2.25 5.102q0 2.058-.827 3.546Q19.477 19 18 19H6q-3.25 0-3.25-5.25T6 8.5h3.25V5.75q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10 5h2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-2.75 0H12v-2h-1.25zm6.75 0v-2h-1.25v2z");
}

</style>
