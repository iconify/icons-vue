<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yif9v5_ot"/><path class="lfuei0b6c"/><path class="ixbvx5bbv"/><path class="cgcgvpbje"/><path class="ri0in5b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-malaysia" /></template>
<style>
.cgcgvpbje {
  fill: var(--svg-color--ffcc4d, #FFCC4D);
  d: path("M9.534 17.233a5.234 5.234 0 0 1-.001-10.466c.715 0 1.397.146 2.018.405A5.958 5.958 0 0 0 8 6a6 6 0 0 0 0 12a5.958 5.958 0 0 0 3.551-1.172a5.21 5.21 0 0 1-2.017.405z");
}

.ixbvx5bbv {
  fill: var(--svg-color--010066, #010066);
  d: path("M18 5H4a4 4 0 0 0-4 4v10h18V5z");
}

.lfuei0b6c {
  fill: var(--svg-color--eee, #EEE);
  d: path("M.555 29h34.891A3.967 3.967 0 0 0 36 27H0c0 .732.211 1.409.555 2zM0 23h36v2H0zm0-4h36v2H0zm0-4h36v2H0zm0-4h36v2H0zm.555-4A3.955 3.955 0 0 0 0 9h36c0-.732-.211-1.41-.555-2H.555z");
}

.ri0in5b3d {
  fill: var(--svg-color--ffcc4d, #FFCC4D);
  d: path("M12.922 8.829l.334 1.62l1.003-1.315l-.402 1.604l1.475-.749l-1.059 1.271l1.654-.035l-1.505.686l1.505.686l-1.654-.035l1.059 1.271l-1.475-.749l.402 1.605l-1.003-1.316l-.334 1.621l-.334-1.621l-1.003 1.316l.402-1.605l-1.475.749l1.058-1.271l-1.653.035l1.505-.686l-1.505-.686l1.653.035l-1.058-1.271l1.475.749l-.402-1.604l1.003 1.315z");
}

.yif9v5_ot {
  fill: var(--svg-color--dd2e44, #DD2E44);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

</style>
