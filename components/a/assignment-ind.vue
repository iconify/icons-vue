<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by-bu4njp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-ind" /></template>
<style>
.by-bu4njp {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h4.7q-.112-.784.388-1.392T12 2t1.296.608T13.685 4h4.7q.69 0 1.152.463T20 5.616v12.769q0 .69-.463 1.153T18.385 20zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212m1.59 7.976q.872-.871.872-2.129t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M5.423 19h13.154q.211-.133.288-.354t.135-.412q-1.35-1.325-3.138-2.087T12 15.385t-3.863.762T5 18.235q.058.19.134.411t.289.354");
}

</style>
