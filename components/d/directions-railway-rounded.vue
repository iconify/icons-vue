<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9zzpbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-railway-rounded" /></template>
<style>
.dg9zzpbgn {
  fill: currentColor;
  d: path("M5 15.116V6q0-1.594 1.636-2.297Q8.274 3 12 3q3.762 0 5.38.694T19 6v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.086.729q.242.162.152.447t-.388.286H7.035q-.298 0-.389-.286q-.09-.285.152-.447L7.885 18q-1.206 0-2.045-.84Q5 16.322 5 15.116M6 11h12V6.539H6zm6.793 4.293q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323");
}

</style>
