<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5nkzd0fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heap-snapshot-large-outline-rounded" /></template>
<style>
.c5nkzd0fo {
  fill: currentColor;
  d: path("M14.5 18q.414 0 .707-.293T15.5 17t-.293-.707T14.5 16t-.707.293T13.5 17t.293.707t.707.293m-5.04-.475q.203 0 .344-.14l5.1-5.1q.14-.14.14-.345t-.14-.344t-.345-.14t-.344.14l-5.119 5.12q-.14.14-.13.334q.009.194.15.335q.14.14.344.14M9.5 13q.414 0 .707-.293T10.5 12t-.293-.707T9.5 11t-.707.293T8.5 12t.293.707T9.5 13m-2.884 8q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zM14 6.962V4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.424V8h-2.962q-.44 0-.739-.299T14 6.961M6 4v4zv16z");
}

</style>
