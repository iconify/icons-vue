<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtnd-nc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flask-empty" /></template>
<style>
.wtnd-nc7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 9.319V3.75H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q7.926 2.25 8 2.25h8q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T16 3.75h-.75v5.569l4.917 9.589q.051.099.071.208q.169.936-.383 1.709t-1.492.916q-.056.009-.113.009H5.75q-.057 0-.113-.009q-.94-.143-1.492-.916t-.383-1.709q.02-.109.071-.208zm1.5.181q0 .181-.083.342l-4.941 9.635q-.016.257.14.476q.17.238.45.297h12.368q.28-.059.45-.297q.156-.219.14-.476l-4.941-9.635q-.083-.161-.083-.342V3.75h-3.5z");
}

</style>
