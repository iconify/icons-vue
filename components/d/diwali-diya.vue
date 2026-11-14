<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffub49bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diwali-diya" /></template>
<style>
.ffub49bli {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.63 10.403q-1.537-.871-1.598-2.633q-.059-1.682 1.354-3.7q.085-.122.211-.202t.273-.107t.292.007q.146.032.268.118q.109.075.184.184q1.413 2.018 1.354 3.7q-.061 1.762-1.598 2.633q-.085.047-.179.072T13 10.5t-.191-.025t-.179-.072M3 11.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 3.65 2.932 5.793Q7.86 19.75 12 19.75q6.464 0 10.171-7.415q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18q-.125-.063-.266-.076q-.14-.013-.275.026q-2.518.719-7.028.533q-1.508-.062-2.266-.062q-1.865 0-5.187-.279Q4.177 11.25 3 11.25");
}

</style>
