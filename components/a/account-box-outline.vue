<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8z97_b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-box-outline" /></template>
<style>
.v8z97_b9l {
  fill: currentColor;
  d: path("M5 18.235q1.35-1.325 3.138-2.088T12 15.385t3.863.762T19 18.235V5.615q0-.23-.192-.423T18.384 5H5.616q-.231 0-.424.192T5 5.616zm9.129-6.03q.871-.87.871-2.128t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm.013-1H18.37q-1.446-1.36-3.064-1.988T12 16.385q-1.65 0-3.293.628T5.629 19m4.962-7.514Q10 10.894 10 10.077t.591-1.409q.592-.591 1.409-.591t1.409.591Q14 9.26 14 10.077t-.591 1.409t-1.409.591t-1.409-.591m1.409.131");
}

</style>
