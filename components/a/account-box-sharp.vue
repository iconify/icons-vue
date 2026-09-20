<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shjmunbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-box-sharp" /></template>
<style>
.shjmunbnl {
  fill: currentColor;
  d: path("M14.129 12.206q.871-.871.871-2.129t-.871-2.129T12 7.077t-2.129.871T9 10.077t.871 2.129t2.129.871t2.129-.871M4 20V4h16v16zm1-1h14v-.766q-1.35-1.325-3.137-2.087T12 15.385t-3.863.762T5 18.235z");
}

</style>
