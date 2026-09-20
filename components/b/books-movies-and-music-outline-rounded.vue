<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu3c0vbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:books-movies-and-music-outline-rounded" /></template>
<style>
.fu3c0vbma {
  fill: currentColor;
  d: path("M5.616 21q-.672 0-1.144-.472T4 19.385V8.529q0-.587.29-1.08q.289-.493.845-.66l6.615-2.047q.789-.246 1.442.239q.654.484.654 1.31V7h.539q.67 0 1.143.472q.472.472.472 1.144v1.538q0 .213-.143.357t-.357.143t-.357-.143t-.143-.357V8.616q0-.27-.173-.443T14.385 8h-8.77q-.269 0-.442.173T5 8.616v10.769q0 .269.173.442t.443.173h5.482q.214 0 .357.143t.143.357t-.143.357t-.357.143zM7.692 7h5.154v-.704q0-.308-.24-.5t-.529-.096zm6.165 12.49q-1.165-1.165-1.165-2.836t1.165-2.836t2.835-1.164t2.836 1.164t1.164 2.836t-1.164 2.835t-2.836 1.165q-1.67 0-2.835-1.165m2.61-1.406l1.627-1.139q.173-.13.173-.328q0-.199-.173-.33l-1.627-1.138q-.211-.13-.426-.022q-.214.109-.214.351v2.277q0 .242.214.35q.215.11.426-.021M5 20V8z");
}

</style>
