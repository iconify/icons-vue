<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhh2rrb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dance-shoe" /></template>
<style>
.uhh2rrb7p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.839 7.25h3.322q-.305-1.125-1.661-1.125T16.839 7.25M21.75 8v12q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.068 0-.136-.012q-.067-.013-.131-.037q-.063-.024-.122-.06t-.109-.081t-.093-.099t-.074-.114t-.052-.126t-.028-.133l-.422-3.588H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-4.25 6.75-4.25q1.702 0 4.291-2.369Q14.268 7.78 15.278 7.4q.275-2.775 3.222-2.775q3.25 0 3.25 3.375");
}

</style>
