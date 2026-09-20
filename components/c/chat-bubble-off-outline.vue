<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmddd6b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-bubble-off-outline" /></template>
<style>
.rmddd6b6i {
  fill: currentColor;
  d: path("M19.385 17v-1q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T19.385 4H6.85l-1-1h13.535q.69 0 1.153.463T21 4.616v10.769q0 .67-.472 1.143q-.472.472-1.143.472m.884 4.685L15.573 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zM4 5.415v12.431L5.846 16h8.738z");
}

</style>
