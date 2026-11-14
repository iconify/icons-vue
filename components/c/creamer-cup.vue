<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgb3v4til"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:creamer-cup" /></template>
<style>
.zgb3v4til {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.807 5.232q.656-.086 1.407-.141L8.081 3.25H6.75zm3.12-.22Q11.446 5 12 5q8.749 0 8.75 2.999q0 .363-.127.681l-2.639 12.475q-.013.063-.037.122q-.024.06-.057.114q-.034.055-.076.103t-.092.089t-.105.071q-.056.032-.116.053t-.124.032q-.063.011-.127.011H6.75q-.064 0-.127-.011t-.124-.032q-.06-.021-.116-.053q-.056-.031-.105-.071q-.05-.041-.092-.089t-.076-.103q-.033-.054-.057-.114q-.024-.059-.037-.122L3.377 8.68Q3.25 8.362 3.25 8q0-1.759 3.007-2.486L4.838 2.853q-.035-.065-.056-.136t-.028-.144t0-.147t.028-.144q.022-.071.057-.136t.082-.122t.104-.104t.122-.082q.166-.088.353-.088h3q.096 0 .189.024t.177.071t.153.114t.12.148zm7.847 5.162Q16.591 11 12 11t-6.774-.826L7.358 20.25h9.284z");
}

</style>
