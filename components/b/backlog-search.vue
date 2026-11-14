<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptyyo5tgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backlog-search" /></template>
<style>
.ptyyo5tgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.75h11.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732H4.75q-2.5 0-2.5-2.5t2.5-2.5M16.25 9H4.75q-2.5 0-2.5 2.5t2.5 2.5h10.328q1.056-.75 2.422-.75q.26 0 .508.027l.01-.009q.732-.732.732-1.768t-.732-1.768T16.25 9m1.25 5.5q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m-6.25.75q1.593 0 2.171 1.015q-.171.582-.171 1.235q0 .823.272 1.533q-.527 1.217-2.272 1.217h-6.5q-2.5 0-2.5-2.5t2.5-2.5zM17.5 19Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
