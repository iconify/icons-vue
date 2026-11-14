<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b84y1jbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-pet-toys" /></template>
<style>
.b84y1jbqz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 6.75Q2.25 6.75 2.25 9q0 1.574 1.101 2.047q-.101.426-.101.953t.101.953Q2.25 13.426 2.25 15q0 2.25 2.25 2.25T6.75 15q0-.159-.011-.308q1.665-.282 1.951-1.942h6.62q.286 1.66 1.951 1.942q-.011.149-.011.308q0 2.25 2.25 2.25T21.75 15q0-1.574-1.101-2.047q.101-.426.101-.953t-.101-.953Q21.75 10.574 21.75 9q0-2.25-2.25-2.25T17.25 9q0 .159.011.308q-1.665.282-1.951 1.942H8.69q-.286-1.66-1.951-1.942q.011-.149.011-.308q0-2.25-2.25-2.25");
}

</style>
