<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm38c737p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-spark-outline-sharp" /></template>
<style>
.fm38c737p {
  fill: currentColor;
  d: path("M4 18v-7.577v.194V6zm-1 1V5h18v6q-.608-.263-1.252-.42q-.645-.157-1.344-.157q-.828 0-1.591.195t-1.436.574H4V18h8.025q.05.275.115.516q.064.24.148.484zM4 8.808h16V6H4zM18.404 21q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15");
}

</style>
