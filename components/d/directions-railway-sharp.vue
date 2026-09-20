<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggtzafbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-railway-sharp" /></template>
<style>
.ggtzafbwe {
  fill: currentColor;
  d: path("M6.385 19.462V19l1.5-1q-1.206 0-2.045-.84Q5 16.322 5 15.116V6q0-1.594 1.636-2.297Q8.274 3 12 3q3.762 0 5.38.694T19 6v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.5 1v.462zM6 11h12V6.539H6zm6.793 4.293q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323");
}

</style>
