<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e278h1bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-test-kit" /></template>
<style>
.e278h1bav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 2.25h4.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T15 3t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014v6.5h1.848q-.089-.509.159-1.04l.659-1.411Q17.522 6.5 18.955 6.5h.795q1.019.001 1.543.874q.524.874.045 1.773l-.752 1.412q-.149.278-.336.491V20q0 2.25-2.25 2.25H6q-2.25 0-2.25-2.25v-8.95q-.187-.213-.336-.491l-.752-1.412q-.479-.899.045-1.773T4.25 6.5h.795q1.433 0 2.039 1.299l.659 1.411q.248.531.159 1.04H9.75v-6.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m1.5 8v-6.5h1.5v6.5z");
}

</style>
