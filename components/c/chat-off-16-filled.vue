<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wwsuo60tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-off-16-filled" /></template>
<style>
.wwsuo60tg {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 1 1-.707.707l-1.564-1.564A6.97 6.97 0 0 1 8 15c-1.29 0-2.5-.351-3.538-.96l-2.804.935a.501.501 0 0 1-.633-.633l.934-2.806A6.97 6.97 0 0 1 1 8a6.97 6.97 0 0 1 1.71-4.582L1.147 1.854a.5.5 0 0 1 0-.708M8 1a7 7 0 0 1 5.895 10.774L9.12 7h1.38a.5.5 0 0 0 0-1H8.121L4.227 2.105A6.97 6.97 0 0 1 8 1M5.5 9a.5.5 0 0 0 0 1h3a.5.5 0 0 0 .467-.326L8.293 9zm-.175-2.968A.5.5 0 0 0 5.5 7h.793z");
}

</style>
