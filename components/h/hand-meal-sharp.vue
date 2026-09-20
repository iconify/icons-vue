<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktkmi2bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hand-meal-sharp" /></template>
<style>
.ktkmi2bxw {
  fill: currentColor;
  d: path("M1 11V9h2.475q.85-2.425 2.863-4.05T11 3.025V2h2v1.025q2.625.3 4.638 1.925T20.5 9H23v2zm7 10v-8h6.8q.35 0 .6.2t.35.475t.038.575t-.338.525L13.975 16H10v1.5h4.5l4.05-3.35q.55-.4 1.163-.5t1.212.05t1.138.513t.912.937l-7 5.85zm-6 1v-9h4v9z");
}

</style>
