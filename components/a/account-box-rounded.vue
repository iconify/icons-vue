<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpdmpybnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-box-rounded" /></template>
<style>
.fpdmpybnu {
  fill: currentColor;
  d: path("M14.129 12.206q.871-.871.871-2.129t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm-.193-1h13.154q.212-.133.289-.354t.134-.412q-1.35-1.325-3.137-2.087T12 15.385t-3.863.762T5 18.235q.058.19.134.411t.289.354");
}

</style>
