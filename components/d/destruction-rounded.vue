<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttuay7csx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:destruction-rounded" /></template>
<style>
.ttuay7csx {
  fill: currentColor;
  d: path("M5.5 20.23q-.633 0-1.066-.433T4 18.731v-3.443q0-.632.434-1.066q.433-.433 1.066-.433h13q.633 0 1.066.433q.434.434.434 1.066v3.443q0 .632-.434 1.066q-.433.434-1.066.434zm1.8-7.941q-.323 0-.615-.079q-.293-.077-.585-.239l-1.621-.944q-.187-.106-.255-.273t-.018-.354t.158-.31t.327-.174l3.444-.593L7.2 5.916q-.056-.218.01-.382q.065-.165.207-.27t.33-.116t.372.121l2.885 2.05l1.738-3.065q.106-.187.283-.267t.364-.031t.31.159q.124.108.174.326l.593 3.482l3.407-.954q.217-.056.382.02q.164.075.27.217t.116.328t-.122.374l-2.03 2.884l.115.064q.521.298.369.865t-.754.567z");
}

</style>
