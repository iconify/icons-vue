<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd0pvdb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:for-you-outline-rounded" /></template>
<style>
.gd0pvdb-e {
  fill: currentColor;
  d: path("M15.135 12.17q1.606-.214 3.048-.65q.384-.143.716.115q.332.257.332.667v6.477q0 .337-.19.599q-.189.263-.495.372q-1.54.533-3.206.815q-1.667.281-3.34.281t-3.34-.281t-3.206-.815q-.306-.11-.495-.372q-.19-.262-.19-.6v-6.476q0-.41.332-.667t.716-.116q1.442.437 3.048.651t3.135.214t3.135-.214m3.096 6.6v-6.212q-1.193.35-2.974.588q-1.782.239-3.257.239t-3.257-.239t-2.974-.588v6.211q1.135.45 2.933.764q1.798.313 3.298.313t3.298-.313t2.933-.764M14.287 4.098q.944.944.944 2.286t-.944 2.287T12 9.616T9.714 8.67t-.945-2.286t.944-2.287T12 3.154t2.286.944m-.71 3.863q.655-.655.655-1.576t-.655-1.576T12 4.154t-1.576.655t-.655 1.576t.655 1.576T12 8.616t1.576-.655M12 16.202");
}

</style>
