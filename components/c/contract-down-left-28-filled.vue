<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="oy2ap_bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contract-down-left-28-filled" /></template>
<style>
.oy2ap_bpo {
  fill: currentColor;
  d: path("M25 21.25A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3h4.5a.75.75 0 0 1 0 1.5h-4.5A2.25 2.25 0 0 0 4.5 6.75V14h6.75A2.75 2.75 0 0 1 14 16.75v6.75h7.25a2.25 2.25 0 0 0 2.25-2.25v-4.5a.75.75 0 0 1 1.5 0zm-.75-9.75a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75v-8.5a.75.75 0 0 1 1.5 0v6.69l7.22-7.22a.75.75 0 1 1 1.06 1.06l-7.22 7.22z");
}

</style>
