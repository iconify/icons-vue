<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gumqqabby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diner" /></template>
<style>
.gumqqabby {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.104 9.412q-.854.746-.854 1.881v7.456q0 2.5 2.5 2.5h12.5q2.5 0 2.5-2.5v-7.456q0-1.135-.854-1.881L18.75 8.41V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 3.25h-2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T15.25 4v1.347l-1.604-1.404Q12 2.504 10.354 3.944zM17.25 4.75v2.347l-.5-.437V4.75zm-2.75 7q.058 0 .116.009q.057.009.112.027q.056.017.108.043t.099.06t.089.074t.076.087t.062.098t.047.107q2.291.102 2.291 2.495q0 2.5-2.5 2.5h-.394q-.803 1-2.606 1h-1q-3.25 0-3.25-3.25v-2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm.75 2.018V15q0 .393-.048.739q.798-.096.798-.989q0-.866-.75-.982");
}

</style>
