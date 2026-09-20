<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5arqcbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-ind-outline-rounded" /></template>
<style>
.q5arqcbhd {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h4.7q-.112-.784.388-1.392T12 2t1.296.608T13.685 4h4.7q.69 0 1.152.463T20 5.616v12.769q0 .69-.463 1.153T18.385 20zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 18.235q1.35-1.325 3.138-2.088T12 15.385t3.863.762T19 18.235V5.615q0-.23-.192-.423T18.384 5H5.616q-.231 0-.424.192T5 5.616zm9.129-6.03q.871-.87.871-2.128t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M5.885 19h12.23v-.173q-1.319-1.24-2.873-1.841T12 16.385q-1.65 0-3.213.591t-2.903 1.813zm4.706-7.514Q10 10.894 10 10.077t.591-1.409q.592-.591 1.409-.591t1.409.591Q14 9.26 14 10.077t-.591 1.409t-1.409.591t-1.409-.591m1.409.131");
}

</style>
