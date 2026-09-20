<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqop65brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-subway-sharp" /></template>
<style>
.rqop65brg {
  fill: currentColor;
  d: path("M6.385 19.462V19l1.5-1q-1.206 0-2.045-.84Q5 16.322 5 15.116V6q0-1.594 1.636-2.297Q8.274 3 12 3q3.763 0 5.381.694T19 6v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.5 1v.462zM6 11h5.5V6.539H6zm6.5 0H18V6.539h-5.5zm-3.207 4.289q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.322.327-.322.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327m7 0q.322-.327.322-.793q0-.467-.327-.79q-.327-.321-.794-.321q-.466 0-.788.326q-.323.327-.323.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327");
}

</style>
