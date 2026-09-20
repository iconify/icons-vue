<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqboer2_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cancel-presentation-rounded" /></template>
<style>
.cqboer2_i {
  fill: currentColor;
  d: path("m11.292 12l-2.246 2.246q-.14.14-.15.344t.15.364t.354.16t.354-.16L12 12.708l2.246 2.246q.14.14.344.15t.364-.15t.16-.354t-.16-.354L12.708 12l2.246-2.246q.14-.14.15-.344t-.15-.364t-.354-.16t-.354.16L12 11.292L9.754 9.046q-.14-.14-.344-.15t-.364.15t-.16.354t.16.354zm-6.676 7q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
