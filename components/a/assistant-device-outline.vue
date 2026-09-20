<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze-4j9byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assistant-device-outline" /></template>
<style>
.ze-4j9byh {
  fill: currentColor;
  d: path("M9.175 8.175Q8 9.35 8 11t1.175 2.825T12 15t2.825-1.175T16 11t-1.175-2.825T12 7T9.175 8.175M12 13q-.825 0-1.412-.587T10 11t.588-1.412T12 9t1.413.588T14 11t-.587 1.413T12 13m4.713 3.713Q17 16.425 17 16t-.288-.712T16 15t-.712.288T15 16t.288.713T16 17t.713-.288M4 22V7q0-2.075 1.463-3.537T9 2h6q2.075 0 3.538 1.463T20 7v15zm2-4h12V7q0-1.25-.875-2.125T15 4H9q-1.25 0-2.125.875T6 7zm0 0h12zm0 0h12z");
}

</style>
