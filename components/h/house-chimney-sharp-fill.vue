<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rdfvh3byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-chimney-sharp-fill" /></template>
<style>
.rdfvh3byb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.3857 2.2071C11.5613 2.0705 11.7775 1.9963 12 1.9963C12.2224 1.9963 12.4386 2.0705 12.6142 2.2071L15 4.0626L15 3.0001C15 2.4478 15.4477 2.0001 16 2.0001L20 2.0001C20.5523 2.0001 21 2.4478 21 3.0001L21 8.7325L23 10.2891L21.7714 11.8673L21 11.2667L21 21.0001C20.9997 21.5523 20.5522 21.9998 20 22.0001L4 22.0001C3.4478 21.9998 3.0002 21.5523 3 21.0001L3 11.2667L2.2285 11.8673L1 10.2891L11.3857 2.2071ZM9 20L15 20L15 18C15 16.3431 13.6569 15 12 15C10.3431 15 9 16.3431 9 18L9 20Z");
}

</style>
