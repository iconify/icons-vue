<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abg5cejrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ardr" /></template>
<style>
.abg5cejrw {
  fill: var(--svg-color--3c87c7, #3c87c7);
  d: path("m11.892 14.403l1.593 2.064l-4.635 3.127zM12 4.406L14.457 8.4L7.905 19.594H3zm0 8.79l3.276-2.393L21 19.593h-4.086z");
}

</style>
