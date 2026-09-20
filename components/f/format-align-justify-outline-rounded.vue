<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc4x-bcyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-align-justify-outline-rounded" /></template>
<style>
.kc4x-bcyj {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21zm0-4q-.425 0-.712-.288T3 16t.288-.712T4 15h16q.425 0 .713.288T21 16t-.288.713T20 17zm0-4q-.425 0-.712-.288T3 12t.288-.712T4 11h16q.425 0 .713.288T21 12t-.288.713T20 13zm0-4q-.425 0-.712-.288T3 8t.288-.712T4 7h16q.425 0 .713.288T21 8t-.288.713T20 9zm0-4q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5z");
}

</style>
