<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-e6tws1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-circle-outline" /></template>
<style>
.r-e6tws1z {
  fill: currentColor;
  d: path("m12 9l-4.288 4.288l.688.689l3.1-3.056v9.656h1v-9.656l3.1 3.056l.689-.688zm-7.83 7.404Q3.6 15.39 3.3 14.28T3 12q0-1.868.709-3.51T5.63 5.633t2.857-1.924T11.997 3t3.51.709t2.859 1.924t1.925 2.857T21 12q0 1.17-.3 2.28t-.87 2.124l-.718-.72q.454-.886.67-1.804T20 12q0-3.35-2.325-5.675T12 4T6.325 6.325T4 12q0 .979.227 1.911t.68 1.774z");
}

</style>
