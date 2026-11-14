<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khjs6x1zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cleaning-supplies" /></template>
<style>
.khjs6x1zb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 8.25h-3.994l2.904-5.394q.071-.132.086-.28t-.028-.292q-.042-.142-.137-.258q-.094-.116-.225-.186q-.065-.035-.136-.057t-.144-.029q-.074-.008-.147-.001q-.074.007-.145.029q-.07.021-.136.055q-.065.035-.122.082q-.057.046-.104.103t-.082.122L13.552 8.25H10.55q.2-.459.2-1v-1q0-2.5-2.5-2.5t-2.5 2.5v1q0 .541.2 1h-1.2q-.828 0-1.414.586T2.75 10.25q0 1.792 1.606 1.978l1.403 8.889q.011.066.032.128q.022.063.054.121q.033.058.075.11q.042.051.093.094t.108.077t.119.057t.128.034q.066.012.132.012h11q.066 0 .132-.012q.065-.011.128-.034q.062-.023.119-.057q.058-.034.108-.077q.051-.043.093-.094t.075-.11t.054-.121t.032-.128l1.403-8.889q1.606-.186 1.606-1.978q0-2-2-2m-12.109 12l-1.263-8h12.244l-1.263 8z");
}

</style>
