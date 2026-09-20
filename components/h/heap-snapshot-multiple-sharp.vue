<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evawvhb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heap-snapshot-multiple-sharp" /></template>
<style>
.evawvhb-j {
  fill: currentColor;
  d: path("M11.782 10.283Q12 10.066 12 9.75q0-.314-.217-.533Q11.566 9 11.25 9q-.314 0-.533.217q-.218.217-.218.532t.217.533t.532.218t.533-.217m-.357 4.506l4.863-4.864l-.713-.714l-4.863 4.864zm4.857-.006q.218-.217.218-.532t-.217-.533t-.532-.218t-.533.217t-.218.532t.217.533t.532.218t.533-.217M7 18V2h8.5L20 6.5V18zm8-11h4l-4-4zM3 22V8h1v13h10v1z");
}

</style>
