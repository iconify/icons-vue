<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxij8nid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lawn-checkerboard" /></template>
<style>
.xtxij8nid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.75h1.171q-1.756 0-2.183 1.704l-1 4q-.266 1.065.41 1.93q.675.866 1.773.866H10.5q.475 0 .85-.1q-.1.375-.1.85v5q0 2.25 2.25 2.25h-11q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.098.025-.193l4-15q.016-.06.042-.116q.025-.056.059-.107t.076-.096t.091-.083q.049-.037.103-.066t.113-.049q.058-.02.119-.03t.122-.01m13.02 16.5h1.98q.098 0 .193-.025q.072-.019.138-.052t.125-.077q.059-.045.107-.101q.049-.055.086-.119t.061-.134t.033-.143q.01-.073.005-.147q-.004-.074-.023-.145l-4-15q-.016-.06-.042-.116q-.025-.056-.059-.107t-.076-.096t-.091-.083q-.049-.037-.103-.066t-.113-.049t-.119-.03t-.122-.01h-7q2.25 0 2.25 2.25v4q0 .475-.1.85q.375-.1.85-.1h4.614q1.705 0 2.166 1.641l1.406 5q.303 1.076-.373 1.968t-1.793.891");
}

</style>
