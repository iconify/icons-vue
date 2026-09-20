<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy6u76ara"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-support-rounded" /></template>
<style>
.zy6u76ara {
  fill: currentColor;
  d: path("M12.942 18H11.5q-3.132 0-5.316-2.183T4 10.504t2.183-5.317T11.498 3q1.566 0 2.93.586q1.364.585 2.383 1.604t1.604 2.379T19 10.5q0 2.658-1.33 4.985t-3.436 3.913q-.211.116-.413.133t-.402-.089t-.321-.276t-.127-.408zm-.886-2.645q.213-.217.213-.523t-.216-.52t-.523-.214t-.52.216q-.214.217-.214.523t.217.52t.523.214t.52-.216M9.459 8.202q.174.067.347-.009t.283-.245q.205-.338.582-.54q.377-.2.868-.2q.736 0 1.197.385t.46 1.042q0 .406-.197.76q-.197.353-.672.828q-.644.627-.925 1.076t-.28.872q0 .197.128.336t.31.14t.305-.14t.146-.341q.049-.31.335-.689t.696-.788q.564-.564.807-1.063q.243-.5.243-.999q0-1.029-.71-1.655t-1.805-.626q-.736 0-1.356.359t-.932.856q-.11.203-.065.388t.235.253");
}

</style>
