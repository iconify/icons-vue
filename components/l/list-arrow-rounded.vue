<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo0bjup7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-arrow-rounded" /></template>
<style>
.eo0bjup7r {
  fill: currentColor;
  d: path("M5.875 18.522q-.136-.053-.266-.18l-2.255-2.219q-.16-.14-.153-.341t.166-.36q.147-.147.338-.15t.337.138l1.631 1.548V6.404q0-.213.144-.357t.357-.143t.356.143t.143.357v10.554l1.65-1.548q.13-.14.327-.14t.346.146q.137.133.137.34t-.14.348L6.737 18.34q-.13.13-.27.182q-.138.053-.297.053t-.296-.053m6.99-.426q-.212 0-.356-.144t-.143-.356t.143-.356t.357-.144H20.5q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm0-5.577q-.212 0-.356-.144t-.143-.357t.143-.356t.357-.143H20.5q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.143zm0-5.577q-.212 0-.356-.144q-.143-.144-.143-.356q0-.213.143-.357t.357-.143H20.5q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
