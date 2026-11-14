<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgi_iqb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-minus" /></template>
<style>
.zgi_iqb0z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.104 9.412q-.854.746-.854 1.881v6.956q0 2.5 2.5 2.5h12.5q2.5 0 2.5-2.5v-6.956q0-1.135-.854-1.881l-6.25-5.47Q12 2.504 10.354 3.944zM14.75 13.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 14.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
