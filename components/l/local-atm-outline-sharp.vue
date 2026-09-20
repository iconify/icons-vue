<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhk5lww7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-atm-outline-sharp" /></template>
<style>
.lhk5lww7n {
  fill: currentColor;
  d: path("M11 17h2v-1h1q.425 0 .713-.288T15 15v-3q0-.425-.288-.712T14 11h-3v-1h4V8h-2V7h-2v1h-1q-.425 0-.712.288T9 9v3q0 .425.288.713T10 13h3v1H9v2h2zm-9 3V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
