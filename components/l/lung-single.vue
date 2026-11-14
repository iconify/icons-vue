<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfy1xacrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lung-single" /></template>
<style>
.xfy1xacrc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v6.811l.75-.75l.75.75V16q0 3.461 4.068 4.478q1.938.484 3.225-.867Q21.25 18.344 21.25 16q0-4.218-2.552-7.234q-2.516-2.973-5.321-2.506q-.065.011-.128.033q-.062.022-.119.055q-.058.032-.109.075t-.093.092q-.043.051-.076.108t-.056.119t-.034.127T12.75 7");
}

</style>
