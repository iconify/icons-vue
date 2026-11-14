<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idxkq1bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:achievement" /></template>
<style>
.idxkq1bdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.75H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2q.009 3.688-3.414 4.191q-.421 1.026-1.27 1.875q-1.413 1.412-3.316 1.64v2.544H15q2.25 0 2.25 2.25T15 21.75H9q-2.25 0-2.25-2.25T9 17.25h2.25v-2.544q-1.903-.228-3.316-1.64q-.849-.849-1.27-1.875Q3.241 10.688 3.25 7V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 4.25h2.25V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75m-.75 3h-1.5V7q-.005 1.985 1.523 2.546Q6.25 9.278 6.25 9zm13 0h-1.5V9q0 .278-.023.546Q19.255 8.985 19.25 7z");
}

</style>
