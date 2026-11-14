<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e5fhmd_zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-edit-28-filled" /></template>
<style>
.e5fhmd_zv {
  fill: currentColor;
  d: path("M14.491 8.866a3.7 3.7 0 0 0-.97 1.712l-.457 1.83c-.381 1.528 1.002 2.913 2.53 2.53l1.832-.457a3.7 3.7 0 0 0 1.712-.969l6.861-6.861v12.101a2.25 2.25 0 0 1-2.25 2.25h-5.751v2.499h1.752a.75.75 0 0 1 .743.648l.007.101a.75.75 0 0 1-.648.744L19.75 25H8.25a.75.75 0 0 1-.102-1.493l.102-.007H10v-2.498H4.25A2.25 2.25 0 0 1 2 18.752V5.25A2.25 2.25 0 0 1 4.25 3h16.106zM11.5 23.5h4.999l-.001-2.499H11.5zM23.1 1.668a2.286 2.286 0 0 1 3.232 3.233l-7.902 7.902a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.087 1.087 0 0 1-1.319-1.318l.458-1.83c.118-.472.362-.904.706-1.248z");
}

</style>
