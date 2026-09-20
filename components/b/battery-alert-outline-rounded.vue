<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-h9wobtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-alert-outline-rounded" /></template>
<style>
.t-h9wobtn {
  fill: currentColor;
  d: path("M8 22q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V3q0-.425.288-.712T11 2h2q.425 0 .713.288T14 3v1h2q.425 0 .713.288T17 5v16q0 .425-.288.713T16 22zm1-2h6V6H9zm0 0h6zm3.713-6.288Q13 13.425 13 13V9q0-.425-.288-.712T12 8t-.712.288T11 9v4q0 .425.288.713T12 14t.713-.288M12 18q.425 0 .713-.288T13 17t-.288-.712T12 16t-.712.288T11 17t.288.713T12 18");
}

</style>
