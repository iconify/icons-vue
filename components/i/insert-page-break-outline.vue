<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t143gmb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-page-break-outline" /></template>
<style>
.t143gmb_y {
  fill: currentColor;
  d: path("M6.616 21q-.667 0-1.141-.475T5 19.386V16.5h1v2.885q0 .269.173.442t.443.173h10.769q.269 0 .442-.173t.173-.443V16.5h1v2.885q0 .666-.475 1.14t-1.14.475zM5 11.5V4.616q0-.667.475-1.141T6.615 3H14.5L19 7.5v4h-1V8h-4V4H6.616q-.27 0-.443.173T6 4.616V11.5zm4.192 3v-1h5.616v1zm7.616 0v-1h5.615v1zm-15.231 0v-1h5.615v1zM12 16.5");
}

</style>
