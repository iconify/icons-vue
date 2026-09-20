<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvvw4cvgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-disabled-check-outline-rounded" /></template>
<style>
.gvvw4cvgc {
  fill: currentColor;
  d: path("M19.266 20.154H3.539q-.349 0-.579-.23t-.23-.578V3.608L1.517 2.392q-.141-.14-.15-.344t.15-.363t.353-.16t.354.16l19.9 19.9q.14.14.153.341t-.153.366q-.16.16-.351.163t-.357-.157zm-15.535-1h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 8h3v-3h-3zm0-4h3v-3h-3zm4 4h6.534l-3-3h-3.534zm4.877-12.54l-.94-.935q-.112-.112-.264-.121q-.152-.01-.283.12t-.13.274t.13.273l.916.916q.242.242.565.245t.565-.24l2.135-2.134q.112-.112.121-.264q.01-.152-.121-.282q-.13-.131-.273-.131t-.273.13zm3.535-3.757q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m.27 14.65q-.144-.144-.144-.357v-4.573q0-.213.144-.357t.356-.143t.357.143t.143.357v4.573q0 .214-.143.357t-.357.143t-.356-.143m-9.539-9.539q-.143-.143-.143-.356V4.154H7.235q-.214 0-.357-.143q-.144-.144-.144-.357t.144-.357q.143-.143.357-.143h3.688q.348 0 .578.23t.23.578v3.65q0 .213-.144.356t-.356.144t-.357-.144");
}

</style>
