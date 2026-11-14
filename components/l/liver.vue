<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgh1facyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:liver" /></template>
<style>
.hgh1facyt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 4.25Q2.25 4.25 2.25 8q0 6.677 1.079 8.835q.03.061.071.115q2.537 3.383 7.879 1.246l.026-.011q6.674-2.966 10.116-9.85q.739-1.478-.062-2.789Q20.566 4.25 19 4.25zm7 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.811-3.22 8.03q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113Q12.75 9.189 12.75 5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
