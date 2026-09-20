<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9v7fb5eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-zr-sharp" /></template>
<style>
.f9v7fb5eo {
  fill: currentColor;
  d: path("M21 5v10.73q0 1.368-.973 2.329q-.973.96-2.354.96H6.327q-1.406 0-2.366-.96Q3 17.098 3 15.73V5zM6.985 15.154h4.4v-.827H8.042l3.249-4.68v-.705H7.116v.827h3.117l-3.248 4.693zm5.773 0h.856v-2.467h1.175l1.555 2.467h.99l-1.722-2.687q.623-.217.937-.643t.315-1.06q0-.914-.564-1.368t-1.727-.454h-1.815zm.856-3.229V9.758h.938q.708 0 1.07.278q.36.278.36.783q0 .531-.363.818t-1.015.288z");
}

</style>
