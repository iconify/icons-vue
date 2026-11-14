<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gezeei4qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:live-gift" /></template>
<style>
.gezeei4qi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 10.25q-.389 0-.75-.014V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6.625q-3.375 0-3.375-3.375v-5.75q0-3.375 3.375-3.375h.393q-.169-.261-.246-.568q-.298-1.194.539-1.868q.711-.573 1.827-.364q1.747.328 2.862 1.973q1.115-1.645 2.862-1.973q1.116-.209 1.827.364q.837.674.539 1.868q-.077.307-.246.568h.393q3.375 0 3.375 3.375v5.75q0 3.375-3.375 3.375H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V10.236q-.361.014-.75.014m1.281-1.537q2.305-.149 2.491-.895q.066-.263-.024-.335q-.173-.14-.61-.058q-1.092.205-1.857 1.288m-2.562 0Q9.954 7.63 8.862 7.425q-.437-.082-.61.058q-.09.072-.024.335q.186.746 2.491.895");
}

</style>
