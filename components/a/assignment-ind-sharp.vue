<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy3_edcdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-ind-sharp" /></template>
<style>
.oy3_edcdr {
  fill: currentColor;
  d: path("M4 20V4h6.316q-.112-.784.388-1.392T12 2t1.296.608T13.685 4H20v16zm8.538-15.77q.212-.213.212-.538t-.213-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212m1.59 7.976q.872-.871.872-2.129t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M5 19h14v-.766q-1.35-1.325-3.137-2.087T12 15.385t-3.863.762T5 18.235z");
}

</style>
