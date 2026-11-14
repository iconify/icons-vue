<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc_5tgyke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-bay" /></template>
<style>
.tc_5tgyke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 10.625q0-5.89-4.07-8.739q-.094-.067-.205-.101q-.11-.035-.225-.035t-.225.035q-.111.034-.205.101Q7.5 4.735 7.5 10.625q0 5.65 3.75 9.203V6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 5.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v13.328q3.75-3.553 3.75-9.203");
}

</style>
