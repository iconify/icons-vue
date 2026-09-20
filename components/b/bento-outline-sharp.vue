<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap0fhm_ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bento-outline-sharp" /></template>
<style>
.ap0fhm_ws {
  fill: currentColor;
  d: path("M2 19V5h20v14zm12-8h6V7h-6zM4 17h8V7H4zm4-3.5q-.625 0-1.062-.437T6.5 12t.438-1.062T8 10.5t1.063.438T9.5 12t-.437 1.063T8 13.5m6 3.5h6v-4h-6z");
}

</style>
