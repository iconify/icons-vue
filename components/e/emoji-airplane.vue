<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ltr0a17zs"/><path class="qdb090c2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-airplane" /></template>
<style>
.ltr0a17zs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.92 17.362l2.974 17.97a5.18 5.18 0 0 1-1.448 4.518l-2.65 2.65l-5.523-18.492m-5.281-5.25L5.524 13.232l2.65-2.65a5.19 5.19 0 0 1 4.519-1.449L30.46 12.3");
}

.qdb090c2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.247 7.862l-.117-.433a2.26 2.26 0 0 0-1.57-1.587l-.429-.117a3.81 3.81 0 0 0-3.882.795L14.878 27.858l-4.696-.623l-3.89 3.934l7.38 3.185l3.05 7.56l3.978-4.02l-.554-4.762L41.48 11.804a3.94 3.94 0 0 0 .768-3.942");
}

</style>
