<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fm-r3tbnm"/><path class="wjnbe8e4c"/><path class="mg6orjbxm"/><path class="phj1eacuc"/><path class="p9jhpobde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-malaysia" /></template>
<style>
.fm-r3tbnm {
  fill: var(--svg-color--eee, #eee);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.mg6orjbxm {
  fill: var(--svg-color--010066, #010066);
  d: path("M18 5H4a4 4 0 0 0-4 4v10.88h18z");
}

.p9jhpobde {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("m12.922 9.269l.334 1.62l1.003-1.315l-.402 1.604l1.475-.749l-1.059 1.271l1.654-.035l-1.505.686l1.505.686l-1.654-.035l1.059 1.271l-1.475-.749l.402 1.605l-1.003-1.316l-.334 1.621l-.334-1.621l-1.003 1.316l.402-1.605l-1.475.749l1.058-1.271l-1.653.035l1.505-.686l-1.505-.686l1.653.035l-1.058-1.271l1.475.749l-.402-1.604l1.003 1.315z");
}

.phj1eacuc {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M9.534 17.673a5.234 5.234 0 0 1-.001-10.466c.715 0 1.397.146 2.018.405A5.96 5.96 0 0 0 8 6.44a6 6 0 0 0 0 12a5.96 5.96 0 0 0 3.551-1.172a5.2 5.2 0 0 1-2.017.405");
}

.wjnbe8e4c {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M.646 29.18h34.708c.354-.544.58-1.18.634-1.863H.012c.054.684.28 1.32.634 1.863M36 23.597v1.863H0v-1.863zm0-1.857v-1.863H0v1.863zM0 16.157v1.863h36v-1.863zM36 14.3v-1.863H0V14.3zM0 9v1.58h36V9q0-.143-.01-.283H.01Q0 8.857 0 9m4-4C2.578 5 1.33 5.742.62 6.86h34.76A4 4 0 0 0 32 5z");
}

</style>
