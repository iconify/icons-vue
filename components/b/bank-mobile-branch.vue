<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8qo6mbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bank-mobile-branch" /></template>
<style>
.y8qo6mbmg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.745 6.445l1.741-1.583q1.514-1.376 3.027 0l1.742 1.583q1.068.972.605 2.305h3.015q3.375 0 3.375 3.375v2.75q0 3.119-2.883 3.356q.133.443.133 1.019q0 2.5-2.5 2.5t-2.5-2.5q0-.564.127-1H9.3q.2.458.2 1q.001 1.036-.732 1.768q-.732.733-1.768.733t-1.768-.733Q4.5 20.286 4.5 19.25q0-.55.206-1.014q-2.956-.202-2.956-3.361v-2.75q0-1.398.989-2.386q.988-.989 2.386-.989H8.14q-.463-1.333.605-2.305m.38 4.805h-2.75q-2.125 0-2.125 2.125T6.375 15.5h2.75q2.125 0 2.125-2.125T9.125 11.25m5.75 0q-2.125 0-2.125 2.125t2.125 2.125h2.75q2.125 0 2.125-2.125t-2.125-2.125z");
}

</style>
