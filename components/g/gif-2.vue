<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw_zlj-ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gif-2" /></template>
<style>
.dw_zlj-ln {
  fill: currentColor;
  d: path("M4.616 16.5q-.667 0-1.141-.475T3 14.886v-5.77q0-.666.475-1.14t1.14-.475h3.789q.479 0 .855.28t.51.72H4.616q-.27 0-.443.173T4 9.116v5.769q0 .269.173.442t.443.173h3.673q.269 0 .442-.173t.173-.442V12.5H6.712v-1h3.192v3.385q0 .666-.475 1.14t-1.14.475zm8.288 0v-9h1v9zm4 0v-9h6v1h-5v3h4v1h-4v4z");
}

</style>
