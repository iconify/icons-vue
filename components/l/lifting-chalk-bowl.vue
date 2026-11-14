<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgt_jbchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lifting-chalk-bowl" /></template>
<style>
.jgt_jbchv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.433 10.25h9.134Q15.232 4.75 12 4.75t-4.567 5.5m10.674 0H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.03-2.866 6.676Q16.095 20.25 12 20.25t-6.884-2.574Q2.25 15.03 2.25 11q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 10.25h2.893q1.583-7 6.107-7t6.107 7");
}

</style>
