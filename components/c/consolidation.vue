<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuoqmqbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:consolidation" /></template>
<style>
.xuoqmqbrp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h1q2.5 0 2.5 2.5v1q0 2.5-2.5 2.5h-1q-2.5 0-2.5-2.5v-1q0-1.036.732-1.768T4.25 1.75m8.25 0h-1Q9 1.75 9 4.25v1q0 2.5 2.5 2.5h1q1.036 0 1.768-.732T15 5.25v-1q0-1.036-.732-1.768T12.5 1.75m6.25 0h1q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-1q-2.5 0-2.5-2.5v-1q0-2.5 2.5-2.5M12 10.972L4.949 9.027q-.143-.04-.291-.021q-.148.018-.278.092q-.13.073-.222.191q-.091.118-.131.262q-.02.071-.025.144q-.005.074.004.147q.009.074.032.144t.06.134q.036.064.084.12t.107.102t.124.078t.138.053l7.25 2q.199.055.398 0l7.25-2q.144-.04.262-.131q.118-.092.191-.222t.092-.278t-.021-.291q-.02-.072-.053-.138t-.078-.124t-.102-.107t-.12-.084q-.064-.037-.134-.06t-.144-.032t-.147-.004t-.144.025zm5.75 6.153q0-3.375-3.375-3.375h-4.75q-1.398 0-2.386.989q-.989.988-.989 2.386v1.75q0 3.375 3.375 3.375h4.75q3.375 0 3.375-3.375z");
}

</style>
