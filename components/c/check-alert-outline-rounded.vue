<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0uvk9buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-alert-outline-rounded" /></template>
<style>
.f0uvk9buu {
  fill: currentColor;
  d: path("m9.55 15.88l8.802-8.801q.146-.146.344-.156t.363.156t.166.357t-.165.356l-8.944 8.95q-.243.243-.566.243t-.566-.243l-4.05-4.05q-.146-.146-.152-.347t.158-.366t.357-.165t.357.165zm5.288 4.574q-1.165-1.162-1.165-2.839q0-1.67 1.165-2.835q1.164-1.165 2.835-1.165t2.836 1.165t1.164 2.835q0 1.677-1.164 2.839q-1.165 1.161-2.836 1.161t-2.835-1.161m2.835-.416q.2 0 .33-.13t.132-.331t-.131-.33t-.331-.131t-.33.13t-.131.331t.13.33t.331.132m0-1.847q.162 0 .273-.111q.112-.112.112-.273v-2.231q0-.162-.112-.273q-.111-.112-.273-.112t-.273.112t-.111.273v2.23q0 .162.111.274t.273.111");
}

</style>
