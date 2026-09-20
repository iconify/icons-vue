<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq8kl3b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bancor" /></template>
<style>
.oq8kl3b8p {
  d: path("M11.083 3L6.588 5.598l4.495 2.61l4.495-2.61zm-5.098 8.83l4.484 2.588V9.234L5.985 6.646zm0 6.581L10.468 21v-5.183l-4.484-2.589zm10.197-6.581l-4.484 2.588V9.234l4.484-2.588zm1.834.34v5.184L11.698 21v-5.183z");
}

</style>
