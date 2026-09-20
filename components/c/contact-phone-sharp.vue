<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgz5drxwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contact-phone-sharp" /></template>
<style>
.cgz5drxwk {
  fill: currentColor;
  d: path("M0 21V3h24v18zm11.125-7.875Q12 12.25 12 11t-.875-2.125T9 8t-2.125.875T6 11t.875 2.125T9 14t2.125-.875M2.1 19h13.8q-1.05-1.875-2.9-2.937T9 15t-4 1.063T2.1 19M19 18l2-2l-1.5-2h-1.65q-.15-.45-.25-.962T17.5 12t.1-1.012t.25-.988h1.65L21 8l-2-2q-1.35 1.05-2.175 2.663T16 12t.825 3.338T19 18");
}

</style>
