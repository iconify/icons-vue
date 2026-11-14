<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj-64hz2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-wipes" /></template>
<style>
.vj-64hz2m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.385 8.251q2.398.047 4.108 1.756q1.757 1.758 1.757 4.243v2q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-8.5q-2.485 0-4.243-1.757Q1.75 18.735 1.75 16.25v-2q0-2.485 1.757-4.243q1.71-1.709 4.108-1.756L6.76 3.123q-.01-.063-.01-.126q0-.064.011-.127q.011-.062.033-.122q.021-.06.052-.116q.032-.055.072-.105t.088-.091t.102-.075t.113-.057q2.892-1.157 5.229.596q1.535 1.151 3.581-.486q.117-.093.26-.134t.292-.025t.279.088t.224.188q.1.125.14.28t.014.312zm-7.25-.001h5.73l.621-3.73q-2.103.955-3.936-.42q-1.436-1.077-3.205-.595zm.615 3.5q-3.5 0-3.5 3.5q0 1.45 1.025 2.475T9.75 18.75h4.5q1.45 0 2.475-1.025t1.025-2.475q0-3.5-3.5-3.5z");
}

</style>
