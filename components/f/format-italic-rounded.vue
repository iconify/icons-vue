<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilkwczocl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-italic-rounded" /></template>
<style>
.ilkwczocl {
  fill: currentColor;
  d: path("M6.346 18.25q-.234 0-.396-.162t-.161-.397t.161-.396t.396-.16h3.077l3.48-10.27H9.828q-.234 0-.396-.162t-.162-.397t.162-.395t.396-.161h7.192q.235 0 .396.162t.162.397t-.162.396q-.161.16-.396.16h-2.961l-3.481 10.27h2.962q.234 0 .395.162t.162.397t-.162.396t-.395.16z");
}

</style>
