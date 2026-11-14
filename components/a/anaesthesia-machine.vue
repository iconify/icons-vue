<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt55b7bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anaesthesia-machine" /></template>
<style>
.pt55b7bew {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25h4q8.388 0 8.735 8.5H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .114-.034.224l-1.248 3.991q-.533 1.848-2.968 1.848t-2.968-1.847l-1.248-3.992q-.022-.071-.03-.144q-.008-.074-.001-.147q.007-.074.027-.145q.021-.071.056-.136q.034-.065.08-.123q.047-.057.103-.105q.057-.047.122-.082t.135-.058q.11-.034.224-.034h2.732q-.342-7-7.232-7H7.75v2.542q3 .354 3 3.708v8.5q0 3.75-3.75 3.75T3.25 18.5V10q0-3.354 3-3.708V3.75H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q4.926 2.25 5 2.25");
}

</style>
