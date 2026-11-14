<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duxgk4y9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cream-carton" /></template>
<style>
.duxgk4y9n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.061 10.002L16.25 5.715V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 3v2.715l-3.811 4.287q-.091.103-.14.231q-.049.129-.049.267v11q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-11q0-.138-.049-.267q-.049-.128-.14-.231M18.75 17.25h-5.5v-2.5h5.5zm-5.5 1.5h5.5v2h-5.5zm1.5-13.5h-5.5v-1.5h5.5zm-1.5 5.25q0-.138-.049-.267q-.049-.128-.14-.231L10.17 6.75h4.993l3.587 4.035v2.465h-5.5z");
}

</style>
