<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtqww9tcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-balance-wallet-sharp" /></template>
<style>
.gtqww9tcw {
  fill: currentColor;
  d: path("M4 20V4h16v3h-9v10h9v3zm8-4V8h9v8zm5.075-2.925Q17.5 12.65 17.5 12t-.425-1.075T16 10.5t-1.075.425T14.5 12t.425 1.075T16 13.5t1.075-.425");
}

</style>
