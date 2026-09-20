<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phpv6bb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:language-international-outline-rounded" /></template>
<style>
.phpv6bb5y {
  fill: currentColor;
  d: path("M2.413 15.356q-.144-.143-.144-.356V9q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v6q0 .213-.144.356t-.357.144t-.355-.144m2.615 0q-.143-.144-.143-.356V9.054q0-.231.16-.393q.16-.161.389-.161h.335q.168 0 .3.08t.2.228l2.616 5.057V9q0-.213.144-.356t.356-.144t.356.144t.144.356v5.946q0 .231-.16.392t-.39.162h-.334q-.168 0-.301-.08t-.2-.228l-2.615-5.057V15q0 .213-.144.356q-.144.144-.357.144t-.356-.144m8.423 0q-.143-.144-.143-.356V9.5h-1.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h4q.212 0 .356.144t.144.357t-.144.356t-.356.143h-1.5V15q0 .213-.144.356t-.357.144t-.356-.144m5.088.144q-.344 0-.576-.232t-.232-.576V9q0-.213.144-.356t.356-.144t.356.144t.144.356v5.5h2.5q.212 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
