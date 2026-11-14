<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0wn9ociw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carrot" /></template>
<style>
.u0wn9ociw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.46 8.473q2.52 2.958 1.752 5.264q-.043.126-.125.23q-.083.104-.197.174l-11.5 7q-.072.044-.153.071q-2.69.896-3.83-.244q-1.077-1.078-.649-4.074q.021-.152.101-.284l7-11.5q.113-.184.306-.281q2.308-1.154 5.826 2.12L18.97 3.97q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-1.748 1.749l2.571-.514q.072-.015.146-.015t.147.014t.14.043t.13.069t.114.093t.093.114t.07.129t.042.141t.015.146q0 .074-.014.147q-.015.072-.043.14t-.069.13q-.041.061-.093.114q-.052.052-.114.093q-.061.041-.129.07q-.068.028-.141.042z");
}

</style>
