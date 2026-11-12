<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8rlbkdii"/><path class="stpgr5ezp"/><path class="h1b59mcwr"/><path class="sss82lbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-bold" /></template>
<style>
.a8rlbkdii {
  fill: currentColor;
  d: path("M11.25 21H10C9.16094 21 8.41528 20.9973 7.75 20.9844V3.01465C8.41527 3.00175 9.16095 3 10 3H11.25V21Z");
}

.h1b59mcwr {
  fill: currentColor;
  d: path("M17.75 3.08008C19.1893 3.19534 20.1339 3.47769 20.8281 4.17188C21.9997 5.34345 22 7.22876 22 11V13C22 16.7712 21.9997 18.6566 20.8281 19.8281C20.1339 20.5223 19.1892 20.8037 17.75 20.9189V3.08008Z");
}

.sss82lbrz {
  fill: currentColor;
  d: path("M6.25 20.9189C4.81075 20.8037 3.86605 20.5223 3.17188 19.8281C2.0003 18.6566 2 16.7712 2 13V11C2 7.22876 2.0003 5.34345 3.17188 4.17188C3.86606 3.47769 4.81071 3.19534 6.25 3.08008V20.9189Z");
}

.stpgr5ezp {
  fill: currentColor;
  d: path("M14 3C14.839 3 15.5847 3.00175 16.25 3.01465V20.9844C15.5847 20.9973 14.8391 21 14 21H12.75V3H14Z");
}

</style>
