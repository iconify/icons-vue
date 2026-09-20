<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1y5dwq8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:conversation-sharp" /></template>
<style>
.x1y5dwq8p {
  fill: currentColor;
  d: path("M6.282 10.283q.218-.217.218-.532q0-.314-.217-.533T5.75 9t-.533.217T5 9.75t.217.533t.532.218t.533-.217m12.5 0Q19 10.066 19 9.75q0-.314-.217-.533Q18.566 9 18.25 9q-.314 0-.533.217q-.218.217-.218.532t.217.533t.532.218t.533-.217M20 21v-2h-3.827v-1H17q1.458 0 2.479-1.021T20.5 14.5h-1q0 1.031-.734 1.766Q18.03 17 17 17h-1v-3h-2.992l1.279-5.106q.667-2.648 2.816-4.271T22 3v18zM4 21H2V3q2.748 0 4.897 1.623t2.817 4.271L10.992 14H8v3H7q-1.031 0-1.766-.734Q4.5 15.53 4.5 14.5h-1q0 1.458 1.021 2.479T7 18h.827v1H4z");
}

</style>
