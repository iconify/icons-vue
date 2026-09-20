<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prnbd6qyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-knight-sharp" /></template>
<style>
.prnbd6qyn {
  fill: currentColor;
  d: path("M5.885 21.02v-4.226l5.538-2.852V11.29l-3.802 1.955q-.223.131-.48.177q-.258.046-.507.046q-.601 0-1.135-.313t-.832-.91q-.273-.54-.223-1.14t.379-1.094l3.004-4.625L6.25 2.98h4.77q2.901 0 4.921 2.075t2.02 5.06v10.903z");
}

</style>
