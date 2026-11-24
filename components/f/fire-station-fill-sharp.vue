<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhrbcws-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fire-station-fill-sharp" /></template>
<style>
.fhrbcws-f {
  fill: currentColor;
  d: path("M21 22h-2v-5a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v5h-2v-5a1 1 0 0 0-1-1H6a1 1 0 0 0-1 1v5H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1M10.214 9.164a1 1 0 0 0-1.171.179a2.4 2.4 0 0 0-.539.862A3.4 3.4 0 0 0 8.3 11.4a3.7 3.7 0 0 0 1.084 2.616A3.7 3.7 0 0 0 12 15.1c.981 0 1.924-.388 2.616-1.084A3.68 3.68 0 0 0 15.7 11.4c0-1.264-.271-2.484-1.193-3.407A1 1 0 0 0 14.4 7.9c-.701-.526-1.244-1.223-1.419-2.096a1.002 1.002 0 0 0-1.606-.585c-.6.481-1.137 1.087-1.37 1.833c-.224.719-.129 1.446.209 2.112m.17 2.768a1.9 1.9 0 0 0 2.166-1.882c0-.322-.041-.645-.144-.95a4 4 0 0 0-.294-.629l-.003-.006q.456.552 1.026.986c.484.519.565 1.269.565 1.949a1.7 1.7 0 0 1-3.316.532M9 22H7v-4h2Zm6 0v-4h2v4Z");
}

</style>
