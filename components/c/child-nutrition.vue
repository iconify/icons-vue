<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu05nqbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:child-nutrition" /></template>
<style>
.pu05nqbsn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.028 3.091Q18 3.803 18 6q0 2.654 1.5 3.141V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21 20.5V9.141Q22.5 8.654 22.5 6q0-3.25-2.25-3.25q-.729 0-1.222.341M1.5 12q0-3.417 2.416-5.834T9.75 3.75t5.834 2.416Q18 8.583 18 12t-2.416 5.834T9.75 20.25t-5.834-2.416Q1.5 15.417 1.5 12m8.251-5.25q2.174 0 3.711 1.538Q15 9.825 15 12t-1.538 3.712Q11.925 17.25 9.75 17.25t-3.712-1.538Q4.5 14.175 4.5 12t1.538-3.712Q7.575 6.75 9.749 6.75z");
}

</style>
