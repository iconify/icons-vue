<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-xs1cbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-organic" /></template>
<style>
.e-xs1cbsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 19.75q15.25 0 15.25-14.75q0-.036-.003-.071q-.007-.074-.029-.144q-.021-.071-.055-.136q-.035-.066-.082-.123q-.046-.057-.103-.104t-.122-.082t-.136-.057t-.144-.029q-.074-.008-.147-.001Q4.25 5.699 4.25 19q0-.15.057-.287q.057-.138.163-.243l7-7q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-7 7q-.105.106-.243.163T5 19.75");
}

</style>
