<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b81ntvbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ifl-outline-sharp" /></template>
<style>
.b81ntvbqc {
  fill: currentColor;
  d: path("M16.774 16.772q.38-.382.38-.928t-.382-.926t-.928-.38t-.926.383t-.38.928t.383.925t.928.38t.925-.382m-3.846-3.846q.38-.383.38-.928t-.382-.926t-.928-.38t-.926.382q-.38.383-.38.928t.382.926t.928.38t.926-.382M9.082 9.08q.38-.382.38-.928t-.383-.926t-.928-.38t-.925.382t-.38.928t.382.926t.928.38t.926-.382M4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
