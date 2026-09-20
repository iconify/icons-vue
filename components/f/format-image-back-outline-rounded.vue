<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-w36z4tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-back-outline-rounded" /></template>
<style>
.b-w36z4tp {
  fill: currentColor;
  d: path("M20 21H4q-.425 0-.712-.288T3 20t.288-.712T4 19h16q.425 0 .713.288T21 20t-.288.713T20 21m0-4H4q-.425 0-.712-.288T3 16t.288-.712T4 15h3v-2H4q-.425 0-.712-.288T3 12t.288-.712T4 11h3V9H4q-.425 0-.712-.288T3 8t.288-.712T4 7h16q.425 0 .713.288T21 8t-.288.713T20 9h-3v2h3q.425 0 .713.288T21 12t-.288.713T20 13h-3v2h3q.425 0 .713.288T21 16t-.288.713T20 17M9 15h6v-2H9zm0-4h6V9H9zm11-6H4q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5m-8 6");
}

</style>
