<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4z9zs12v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-left-right-circle-rounded" /></template>
<style>
.h4z9zs12v {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701m1.514-5.48q.14-.14.14-.354t-.14-.353L8.396 12.5h7.227l-1.592 1.612q-.14.14-.15.344t.15.363t.354.16t.354-.16l2.215-2.254q.242-.242.242-.565t-.242-.565L14.738 9.2q-.14-.16-.344-.16t-.363.16t-.16.354t.16.354l1.592 1.592H8.396l1.592-1.611q.14-.141.15-.345t-.13-.344q-.14-.16-.354-.15T9.3 9.2l-2.234 2.235q-.243.242-.243.565t.243.566L9.3 14.819q.14.14.354.15t.354-.15");
}

</style>
