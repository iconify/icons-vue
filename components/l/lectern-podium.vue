<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llxt-ytsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lectern-podium" /></template>
<style>
.llxt-ytsu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.32 8.355l15.034-4.177q.904-.251 1.65.317T21.75 6v.378q0 1.684-1.615 2.159l-5.885 1.73v8.983h4.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 20q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4.25v-7.659l-4.149 1.221q-2.084.613-2.771-1.448l-.043-.131q-.304-.915.149-1.767q.454-.852 1.384-1.111m8.43 2.354l-1.5.441v8.1h1.5z");
}

</style>
