<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqd74tbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attachment-outline" /></template>
<style>
.bqd74tbpc {
  fill: currentColor;
  d: path("M8.462 17.173q-2.274 0-3.868-1.565Q3 14.042 3 11.788q0-2.272 1.594-3.847t3.868-1.575h8.73q1.587 0 2.698 1.09Q21 8.549 21 10.136t-1.11 2.678q-1.111 1.09-2.698 1.09H8.923q-.88 0-1.517-.616t-.637-1.499t.627-1.517t1.527-.637h8.308v1H8.923q-.479 0-.816.328t-.338.807t.338.807t.816.328h8.289q1.165-.006 1.977-.805T20 10.135t-.821-1.968t-1.987-.801h-8.73Q6.608 7.36 5.304 8.648T4 11.788q0 1.828 1.305 3.1t3.157 1.285h8.769v1z");
}

</style>
