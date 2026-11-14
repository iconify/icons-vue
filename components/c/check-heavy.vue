<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km5ve4b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:check-heavy" /></template>
<style>
.km5ve4b7c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.531 10.909l.878-.878q.659-.66 1.591-.66t1.592.66l1.377 1.378q.22.22.531.22t.53-.22l6.379-6.378q.659-.66 1.591-.66t1.592.66l.877.878q.66.659.66 1.591t-.66 1.591l-9.378 9.378q-.659.66-1.591.66t-1.591-.66l-4.378-4.378q-.66-.659-.66-1.591t.66-1.591");
}

</style>
