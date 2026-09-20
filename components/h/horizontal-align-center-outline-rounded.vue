<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd7-c-buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-align-center-outline-rounded" /></template>
<style>
.sd7-c-buv {
  fill: currentColor;
  d: path("m15.8 12.5l1.746 1.746q.14.14.15.344t-.15.364t-.354.16t-.353-.16l-2.382-2.382q-.138-.137-.19-.276q-.054-.14-.054-.298t.053-.296q.053-.136.19-.274l2.383-2.382q.14-.14.344-.15t.363.15t.16.354t-.16.354L15.8 11.5h4.7q.213 0 .356.144t.144.357t-.144.356t-.356.143zm-3.3 6q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356v-13q0-.213.144-.356T12.001 5t.356.144t.143.356zm-4.3-6H3.5q-.213 0-.356-.144T3 11.999t.144-.356t.356-.143h4.7L6.454 9.754q-.14-.14-.15-.344t.15-.364t.354-.16t.353.16l2.382 2.382q.138.137.19.276q.053.14.053.298t-.052.296t-.19.274L7.16 14.954q-.14.14-.344.15t-.363-.15t-.16-.354t.16-.354z");
}

</style>
