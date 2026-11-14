<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc3bsqbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-live" /></template>
<style>
.bc3bsqbyn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.812 4.121l5.122 2.955q1.689.974 1.689 2.924t-1.689 2.924l-5.122 2.955q-1.688.973-3.375-.001q-1.687-.975-1.687-2.923v-5.91q0-1.948 1.687-2.923q1.687-.974 3.375-.001m5.829 10.52Q13.25 16.032 13.25 18t1.391 3.359T18 22.75t3.359-1.391T22.75 18t-1.391-3.359T18 13.25t-3.359 1.391m2.694 2.609q-.243-1.061-1.172-2.123q.73-.377 1.837-.377q1.108 0 1.839.378q-.903 1.042-1.134 2.122zm-2.228-1.047q.441.534.629 1.047h-.937q.083-.594.308-1.047m5.19 1.047q.176-.522.598-1.043q.223.451.306 1.043zm-4.561 1.5q-.188.513-.629 1.047q-.225-.453-.308-1.047zm4.103 2.122q-.731.378-1.839.378q-1.107 0-1.837-.377q.929-1.062 1.172-2.123h1.37q.231 1.08 1.134 2.122m.458-2.122h.904q-.083.592-.306 1.043q-.422-.521-.598-1.043");
}

</style>
