<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukatmkbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-person-24-regular" /></template>
<style>
.ukatmkbny {
  fill: currentColor;
  d: path("M20.228 17c.978 0 1.772.793 1.772 1.773v.102C22 20.431 20.714 22 17.5 22S13 20.437 13 18.875v-.102c0-.98.794-1.773 1.772-1.773zM11.249 3a.75.75 0 0 1 0 1.5H8.116a.75.75 0 0 0-.65.376l-3.898 6.77a.75.75 0 0 0-.007.733l3.614 6.627a.949.949 0 0 0 1.736-.167l4.492-14.12a2.47 2.47 0 0 1 4.492-.483l3.823 6.641c.4.695.4 1.551 0 2.246l-.976 1.693a3.49 3.49 0 0 0-.488-3.475l-3.66-6.356a.969.969 0 0 0-1.761.19L10.34 19.294a2.449 2.449 0 0 1-4.482.43l-3.615-6.626a2.25 2.25 0 0 1 .026-2.2l3.897-6.771A2.25 2.25 0 0 1 8.116 3zm6.251 8a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
