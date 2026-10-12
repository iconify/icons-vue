<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6g9jwb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bath-salt-sharp" /></template>
<style>
.n6g9jwb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h6v3h-6zm-1.5 6h9v12.5h-9zm13.77 11.13l-.84.84l-.28.28l-.28-.28l-.84-.84l-.28-.28l.28-.28l.84-.84l.28-.28l.28.28l.84.84l.28.28zm4.45 0l-.84.84l-.28.28l-.28-.28l-.84-.84l-.28-.28l.28-.28l.84-.84l.28-.28l.28.28l.84.84l.28.28zm-2.25-5l-.84.84l-.28.28l-.28-.28l-.84-.84l-.28-.28l.28-.28l.84-.84l.28-.28l.28.28l.84.84l.28.28z");
}

</style>
