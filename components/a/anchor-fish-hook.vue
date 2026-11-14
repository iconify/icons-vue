<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3br682hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anchor-fish-hook" /></template>
<style>
.r3br682hu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 16V2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 1.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13q-.028.068-.043.141T15.25 2v14q0 3.75-3.75 3.75T7.75 16v-2.805l1.495 1.36q.111.1.251.151t.29.043t.284-.071t.235-.173t.151-.251t.043-.29t-.071-.284t-.173-.235l-2.75-2.499v-.001q-.104-.094-.235-.145q-.13-.05-.27-.05l-.033.001h-.003q-.139.007-.267.063q-.128.057-.227.156l-.025.025q-.094.104-.145.235q-.05.13-.05.27V16q0 2.175 1.538 3.712Q9.325 21.25 11.5 21.25t3.712-1.538Q16.75 18.175 16.75 16");
}

</style>
