<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjvly-b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cup-size-medium" /></template>
<style>
.xjvly-b9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.008 5.25h.492q2.25 0 2.25 2.25q0 1.886-1.581 2.191l-1.425 11.402q-.008.067-.029.132q-.02.065-.052.125t-.074.114t-.093.098t-.109.08t-.122.059q-.063.025-.13.037T16 21.75H8q-.068 0-.135-.012t-.13-.037q-.064-.024-.122-.059t-.109-.08t-.093-.098t-.074-.114t-.052-.125q-.021-.065-.029-.132L5.831 9.691Q4.25 9.386 4.25 7.5q0-2.25 2.25-2.25h.492l.812-2.029q.041-.104.112-.191q.07-.088.164-.151q.093-.063.2-.096t.22-.033h7q.112 0 .22.033q.107.033.2.096t.164.151t.112.191zm-8.4 0h6.784l-.4-1H9.008zm8.042 4.5h-9.3l1.312 10.5h6.676z");
}

</style>
