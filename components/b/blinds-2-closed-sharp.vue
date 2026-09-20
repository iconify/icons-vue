<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h50w1jh7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-2-closed-sharp" /></template>
<style>
.h50w1jh7p {
  fill: currentColor;
  d: path("M5.385 3h13.23q.981 0 1.683.702T21 5.394v2.375h-2V21H4.98V7.77H3V5.384q0-.994.696-1.69T5.385 3m.55 17h12.111l-1.554-2.789h-1.28v.558q0 .213-.144.357t-.356.143q-.195 0-.347-.143q-.153-.144-.153-.357v-.557H7.489zm9.276-9.442h2.835l-1.554-2.789h-1.28zm0 4.711h2.835l-1.554-2.788h-1.28zm-9.276 0h8.276v-2.788H7.49zm0-4.711h8.276V7.769H7.49z");
}

</style>
