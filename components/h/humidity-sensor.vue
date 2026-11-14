<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktgzj1heu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:humidity-sensor" /></template>
<style>
.ktgzj1heu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75m-2.921 3.236q.015-.017.032-.032q.054-.051.116-.09t.132-.065t.142-.039q.073-.012.147-.01q.074.003.146.019q.072.017.139.047t.127.073t.111.097q4.204 4.467 4.204 7.264q0 1.968-1.391 3.359T12 18t-3.359-1.391T7.25 13.25q0-2.797 4.204-7.264");
}

</style>
