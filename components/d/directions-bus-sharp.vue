<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th3mixbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-bus-sharp" /></template>
<style>
.th3mixbwm {
  fill: currentColor;
  d: path("M7.77 20H6.538v-2.396q-.489-.212-1.014-.901T5 15.115V6q0-1.556 1.684-2.278Q8.37 3 12 3q3.763 0 5.382.694T19 6v9.116q0 .898-.525 1.587q-.525.69-1.014.9V20h-1.23v-2H7.769zM6 11h12V6.539H6zm3.293 4.289q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.322.327-.322.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327m7 0q.322-.327.322-.793q0-.467-.327-.79q-.327-.321-.794-.321q-.466 0-.788.326q-.323.327-.323.793q0 .467.327.79q.327.322.793.322q.467 0 .79-.327");
}

</style>
