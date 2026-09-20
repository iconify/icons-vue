<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llopp5e4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:checklist-rounded" /></template>
<style>
.llopp5e4u {
  fill: currentColor;
  d: path("m5.814 16.502l3.896-3.896q.146-.146.353-.153q.208-.007.354.159q.14.146.14.354q0 .207-.14.353l-4.013 4.02q-.243.242-.566.242t-.565-.243L3.335 15.4q-.14-.14-.131-.344t.15-.344t.344-.14t.344.14zm0-7.23L9.71 5.374q.146-.146.353-.153q.208-.007.354.159q.14.146.14.353q0 .208-.14.354l-4.013 4.02q-.243.242-.566.242t-.565-.242L3.334 8.169q-.14-.14-.13-.344t.15-.344t.344-.14t.344.14zm7.705 6.844q-.213 0-.356-.144q-.144-.143-.144-.356q0-.214.144-.357t.356-.143h7q.214 0 .357.143t.143.357t-.143.356t-.357.144zm0-7.231q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.144h7q.214 0 .357.144q.143.143.143.356q0 .214-.143.357t-.357.143z");
}

</style>
