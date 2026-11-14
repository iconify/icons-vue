<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txbamn9fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:low-key" /></template>
<style>
.txbamn9fy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.379 3.604Q20.75 6.664 20.75 12t-4.371 8.396q-.06.043-.128.072q-.068.03-.14.046t-.146.018q-.073.001-.146-.011t-.142-.04t-.131-.066q-.062-.04-.116-.091q-.053-.051-.095-.112q-.043-.06-.072-.128q-.03-.068-.046-.14t-.018-.146q-.001-.074.011-.146q.013-.073.04-.142t.066-.131t.091-.116t.112-.095Q19.25 16.555 19.25 12t-3.731-7.168q-.061-.042-.112-.095q-.051-.054-.091-.116q-.039-.062-.066-.131t-.04-.142t-.011-.146q.002-.074.018-.146t.046-.14t.072-.128t.095-.112t.116-.091t.131-.066t.142-.04q.073-.012.146-.011q.074.002.146.018t.14.046t.128.072M5.727 7.227Q3.75 9.204 3.75 12t1.977 4.773T10.5 18.75t4.773-1.977T17.25 12t-1.977-4.773T10.5 5.25T5.727 7.227");
}

</style>
