<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op9hiebua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:curtains-outline-sharp" /></template>
<style>
.op9hiebua {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm3-1h4.43q-.2-1.942-1.284-3.884T6 12.631zM6 5v6.37q2.062-.545 3.146-2.486T10.431 5zm1.11 7q1.988.856 3.067 2.883T11.45 19h1.1q.194-2.09 1.273-4.117T16.891 12q-2.008-.856-3.087-2.883T12.53 5h-1.08q-.194 2.09-1.273 4.117T7.11 12M18 5h-4.45q.2 1.942 1.285 3.884T18 11.369zm0 14v-6.37q-2.08.545-3.153 2.486T13.575 19zM6 5v6.37zm12 0v6.37zm0 14v-6.37zM6 19v-6.37z");
}

</style>
