<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o56kpvqjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-portrait-outline" /></template>
<style>
.o56kpvqjy {
  fill: currentColor;
  d: path("M17.385 21H6.615q-.69 0-1.152-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616v14.769q0 .69-.462 1.153T17.384 21M6.615 20h10.77q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T17.385 4H6.615q-.269 0-.442.173T6 4.616v14.769q0 .269.173.442t.443.173M6 20V4z");
}

</style>
