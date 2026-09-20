<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cte5vbc-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backpack-outline-sharp" /></template>
<style>
.cte5vbc-h {
  fill: currentColor;
  d: path("M5 21V8.399q0-1.26.85-2.214T8 5.054V3h2v2h4V3h2v2.054q1.3.177 2.15 1.129t.85 2.22V21zm1-1h12V8.404q0-.992-.734-1.698Q16.53 6 15.5 6h-7q-1.031 0-1.766.706Q6 7.412 6 8.404zm9.116-4.423h1v-2.923H7.885v1h7.23zM12 13");
}

</style>
