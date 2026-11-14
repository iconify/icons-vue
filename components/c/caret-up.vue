<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-9svvb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-up" /></template>
<style>
.d-9svvb3h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.649 8.174l3.06 3.295q1.003 1.079.414 2.43T15.06 15.25H8.94q-1.474 0-2.063-1.351t.415-2.43l3.059-3.295q.668-.719 1.649-.719t1.648.719z");
}

</style>
