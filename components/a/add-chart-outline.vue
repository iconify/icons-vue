<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzy_tq3th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart-outline" /></template>
<style>
.kzy_tq3th {
  fill: currentColor;
  d: path("M5.116 20q-.691 0-1.153-.462T3.5 18.384V5.616q0-.691.463-1.153T5.115 4h9.308v1H5.116q-.27 0-.443.173t-.173.443v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443V9.077h1v9.308q0 .69-.462 1.152T17.884 20zm2.115-3.5h1v-6h-1zm3.769 0h1v-9h-1zm3.77 0h1v-3h-1zM17.5 8V6h-2V5h2V3h1v2h2v1h-2v2zm-6 4");
}

</style>
