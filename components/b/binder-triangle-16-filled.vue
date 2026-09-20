<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-yw34-qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:binder-triangle-16-filled" /></template>
<style>
.h-yw34-qv {
  fill: currentColor;
  d: path("M3.75 1A1.75 1.75 0 0 0 2 2.75V3h-.5a.5.5 0 0 0 0 1H2v2h-.5a.5.5 0 0 0 0 1H2v2h-.5a.5.5 0 0 0 0 1H2v.25c0 .966.784 1.75 1.75 1.75h.857L11 4.187V2.75A1.75 1.75 0 0 0 9.25 1zM5.5 4h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1m8.5-.5a.5.5 0 0 0-.887-.317l-9 11A.5.5 0 0 0 4.5 15h7.75A1.75 1.75 0 0 0 14 13.25zm-2.95 5.6a.25.25 0 0 1 .45.15V12a.5.5 0 0 1-.5.5H9a.25.25 0 0 1-.2-.4z");
}

</style>
