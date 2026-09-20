<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6kcbzydl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grocery-sharp" /></template>
<style>
.i6kcbzydl {
  fill: currentColor;
  d: path("M3 19v-8.896l2.458-5.488H3.962V3h7.077v1.616H9.542l2.497 5.646q-1.43.877-2.247 2.456t-.817 3.238q0 .75.179 1.559T9.696 19zm13 2q-2.077 0-3.538-1.461T11 16t1.462-3.538T16 11t3.539 1.462T21 16t-1.461 3.539T16 21m0-11.385q-.646-.173-1.073-.696T14.5 7.692t.427-1.227T16 5.77zq.173-.646.696-1.073t1.227-.427t1.227.427t.696 1.073z");
}

</style>
