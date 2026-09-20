<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mygs5_g_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contact-card-24-filled" /></template>
<style>
.mygs5_g_l {
  fill: currentColor;
  d: path("M19.75 4A2.25 2.25 0 0 1 22 6.25v11.505a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 17.755V6.25A2.25 2.25 0 0 1 4.25 4zm-10 8.5h-3.5a.75.75 0 0 0-.743.648l-.007.102v.492l.008.108C5.67 14.964 6.602 15.5 8 15.5c1.331 0 2.24-.486 2.464-1.494l.028-.155l.008-.108v-.493a.75.75 0 0 0-.648-.743zm8 .496h-4.498l-.102.007a.75.75 0 0 0 0 1.486l.102.007h4.498l.102-.007a.75.75 0 0 0 0-1.486zM8 8.502a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m9.75.998h-4.498l-.102.007a.75.75 0 0 0 0 1.486l.102.007h4.498l.102-.007a.75.75 0 0 0 0-1.486z");
}

</style>
