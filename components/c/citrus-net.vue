<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5n2ltbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:citrus-net" /></template>
<style>
.v5n2ltbov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12 4.385l-1.945-2.14q-.1-.11-.235-.173q-.135-.064-.284-.071t-.29.043t-.251.151t-.173.235q-.064.135-.071.284t.043.29q.051.14.151.251l1.442 1.586Q3.5 7.931 3.5 15v2q0 2.071 1.464 3.536Q6.429 22 8.5 22h7q2.071 0 3.536-1.464Q20.5 19.071 20.5 17v-2q0-7.069-6.887-10.159l1.442-1.586q.1-.111.151-.251t.043-.29q-.007-.149-.071-.284t-.173-.235q-.111-.1-.251-.151t-.29-.043t-.284.071t-.235.173zM8.75 11.75Q8.75 8.5 12 8.5t3.25 3.25q0 .568-.099 1.036q2.599.308 2.599 3.214q0 3.25-3.25 3.25q-1.689 0-2.5-.878q-.811.878-2.5.878q-3.25 0-3.25-3.25q0-2.906 2.599-3.214q-.099-.468-.099-1.036");
}

</style>
