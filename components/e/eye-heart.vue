<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdyk93b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-heart" /></template>
<style>
.kdyk93b4z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.819 9.436Q4.443 3.75 9.75 3.75t7.931 5.686q.069.149.069.314t-.069.314Q15.057 15.75 9.75 15.75t-7.931-5.686q-.069-.149-.069-.314t.069-.314M6.5 9.75Q6.5 13 9.75 13T13 9.75T9.75 6.5T6.5 9.75m1.5 0q0 1.75 1.75 1.75t1.75-1.75T9.75 8T8 9.75m9.599 11.884Q14.25 19.513 14.25 17q0-2.75 2.5-2.75q.741 0 1.25.357q.509-.357 1.25-.357q2.5 0 2.5 2.75q0 2.513-3.349 4.634q-.09.057-.192.086q-.102.03-.209.03t-.209-.03q-.102-.029-.192-.086");
}

</style>
