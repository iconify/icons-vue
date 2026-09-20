<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azngo4dre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:checklist-rtl-rounded" /></template>
<style>
.azngo4dre {
  fill: currentColor;
  d: path("m16.08 16.502l3.897-3.896q.146-.146.354-.153t.354.159q.14.146.14.354q0 .207-.14.353l-4.014 4.02q-.242.242-.565.242t-.566-.243L13.603 15.4q-.14-.14-.13-.344q.009-.204.15-.344t.344-.14t.344.14zm0-7.23l3.897-3.897q.146-.146.354-.153t.354.159q.14.146.14.353q0 .208-.14.354l-4.014 4.02q-.242.242-.565.242t-.566-.242l-1.938-1.939q-.14-.14-.13-.344q.009-.204.15-.344t.344-.14t.344.14zM3.5 16.115q-.213 0-.357-.144Q3 15.829 3 15.616q0-.214.143-.357t.357-.143h7q.214 0 .357.143t.143.357t-.143.356t-.357.144zm0-7.231q-.213 0-.357-.144T3 8.385t.143-.357q.144-.144.357-.144h7q.214 0 .357.144q.143.143.143.357q0 .213-.143.356t-.357.144z");
}

</style>
