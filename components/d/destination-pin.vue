<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exwjexsxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:destination-pin" /></template>
<style>
.exwjexsxz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m9.38-2.528l.088.205q.175.405.617.446l.222.021q.804.073 1.055.844q.251.772-.359 1.306l-.165.146q-.333.293-.236.726l.048.218q.179.786-.476 1.263t-1.352.063l-.192-.114q-.38-.225-.762.001l-.19.113q-.697.413-1.352-.063q-.655-.477-.475-1.267l.047-.213q.097-.434-.236-.727l-.167-.147q-.608-.533-.357-1.305t1.058-.844l.219-.021q.442-.041.618-.448l.087-.203q.32-.744 1.13-.744t1.13.744");
}

</style>
