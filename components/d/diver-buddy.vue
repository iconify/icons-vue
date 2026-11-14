<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkq6k3kpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diver-buddy" /></template>
<style>
.hkq6k3kpc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6.5q0-1.139.805-1.945q.806-.805 1.945-.805h4q2.75 0 2.75 2.75v.36q6.501 1.145 6.964 5.89H19.5q2.75 0 2.75 2.75v2q0 2.75-2.75 2.75h-.75q-.167 0-.318-.071t-.258-.199l-.674-.808l-.674.808q-.107.128-.258.199t-.318.071h-.75q-2.75 0-2.75-2.75v-2q0-2.75 2.75-2.75h1.199q-.477-3.399-5.449-4.364V8.5q0 2.75-2.75 2.75h-.75q-.167 0-.318-.071t-.258-.199l-.674-.808l-.674.808q-.107.128-.258.199t-.318.071H4.5q-2.75 0-2.75-2.75z");
}

</style>
