<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf87x_zcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-box-outline-sharp" /></template>
<style>
.wf87x_zcr {
  fill: currentColor;
  d: path("M5 18.235q1.35-1.325 3.138-2.088T12 15.385t3.863.762T19 18.235V5H5zm9.129-6.03q.871-.87.871-2.128t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M4 20V4h16v16zm6.591-8.514Q10 10.894 10 10.077t.591-1.409q.592-.591 1.409-.591t1.409.591Q14 9.26 14 10.077t-.591 1.409t-1.409.591t-1.409-.591M5.63 19h12.74q-1.446-1.36-3.064-1.988T12 16.385q-1.65 0-3.293.628T5.629 19");
}

</style>
