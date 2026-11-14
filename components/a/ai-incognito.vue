<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk-3w188x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-incognito" /></template>
<style>
.uk-3w188x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.975 9.25l1.82-5.006q.04-.109.11-.2t.165-.158t.204-.101q.111-.035.226-.035h9q.115 0 .226.035q.11.034.204.101q.095.066.165.158q.07.091.11.2l1.82 5.006H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 10.074 2.25 10t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 9.25zm1.596 0h10.858l-1.454-4h-7.95zM4.25 16.5q0-3.25 3.25-3.25q2.55 0 3.099 2h2.802q.549-2 3.099-2q3.25 0 3.25 3.25t-3.25 3.25q-3.122 0-3.245-3h-2.51q-.123 3-3.245 3q-3.25 0-3.25-3.25");
}

</style>
