<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucqdn_4te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-music-vinyl" /></template>
<style>
.ucqdn_4te {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m3.501 0q0 4.726 4.44 6.343q.07.025.143.036q.073.012.147.008q.073-.003.145-.02t.139-.049q.067-.031.126-.075q.06-.044.11-.098t.088-.118q.038-.063.064-.132q.025-.07.036-.143q.012-.073.008-.147q-.003-.073-.02-.145t-.049-.139t-.075-.126q-.044-.06-.098-.11t-.118-.088t-.132-.064Q6.751 15.676 6.751 12t3.454-4.933q.14-.051.25-.152t.173-.236t.069-.284t-.044-.29q-.026-.069-.064-.132t-.088-.118t-.11-.098t-.126-.075t-.139-.049q-.072-.017-.145-.02q-.074-.004-.147.008q-.073.011-.143.036Q5.251 7.274 5.251 12M15 12q0-3-3-3t-3 3t3 3t3-3");
}

</style>
