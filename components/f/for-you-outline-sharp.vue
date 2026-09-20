<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne94nwbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:for-you-outline-sharp" /></template>
<style>
.ne94nwbmr {
  fill: currentColor;
  d: path("M15.744 12.068q1.912-.316 3.487-.876V19.5q-1.423.598-3.42.972q-1.995.374-3.811.374t-3.812-.374t-3.419-.972v-8.308q1.575.56 3.487.876t3.744.317t3.744-.317m2.487 6.701v-6.211q-1.193.35-2.974.588q-1.782.239-3.257.239t-3.257-.239t-2.974-.588v6.211q1.135.45 2.933.764q1.798.313 3.298.313t3.298-.313t2.933-.764M14.287 4.098q.944.944.944 2.286t-.944 2.287T12 9.616T9.714 8.67t-.945-2.286t.944-2.287T12 3.154t2.286.944m-.71 3.863q.655-.655.655-1.576t-.655-1.576T12 4.154t-1.576.655t-.655 1.576t.655 1.576T12 8.616t1.576-.655M12 16.202");
}

</style>
