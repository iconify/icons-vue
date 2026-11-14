<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4-frob3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delta-change" /></template>
<style>
.h4-frob3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.314 3.197L4.011 19.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.511L12.686 3.197q-.056-.128-.156-.227q-.099-.1-.227-.156q-.068-.03-.14-.046t-.146-.018t-.147.011q-.072.013-.141.04q-.069.026-.131.066q-.063.04-.116.091t-.096.111q-.042.061-.072.128M12 5.358l6.349 14.392H5.651z");
}

</style>
