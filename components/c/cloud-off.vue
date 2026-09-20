<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2bcge-io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cloud-off" /></template>
<style>
.q2bcge-io {
  fill: currentColor;
  d: path("M20.454 21.87L17.612 19H6.5q-1.896 0-3.198-1.302T2 14.5q0-1.829 1.226-3.098t2.87-1.368q.018-.373.208-.925q.19-.553.438-.951l-3.88-3.881l.707-.708l17.593 17.593zm.454-3.812L8.78 5.937q.875-.523 1.612-.73T12 5q2.502 0 4.251 1.749T18 11v1h.616q1.436.046 2.41 1.055T22 15.5q0 .687-.25 1.332t-.842 1.226");
}

</style>
