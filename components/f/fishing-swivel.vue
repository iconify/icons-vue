<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5sw39ous"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-swivel" /></template>
<style>
.j5sw39ous {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 5.25q0-3.5 3.5-3.5t3.5 3.5q0 2.256-1.454 3.058q.454.627.454 1.442v1q0 1.036-.732 1.768q-.597.597-1.396.707l-2.122 2.547V19q0 1.75 1.75 1.75T13.75 19v-3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V19q0 3.25-3.25 3.25T8.75 19v-3.5q0-.132.045-.255q.045-.124.129-.225l1.701-2.041Q9.5 12.427 9.5 10.75v-1q0-.925.342-1.507Q8.5 7.417 8.5 5.25");
}

</style>
