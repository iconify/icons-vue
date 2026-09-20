<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loot9ibkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-seat-rounded" /></template>
<style>
.loot9ibkj {
  fill: currentColor;
  d: path("M4.643 20.164q-.143-.144-.143-.356v-2.885q0-.666.475-1.14t1.14-.475h11.77q.666 0 1.14.474t.475 1.141v2.885q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356v-2.885q0-.27-.173-.442q-.173-.173-.442-.173H6.115q-.269 0-.442.173t-.173.442v2.885q0 .212-.144.356t-.357.144t-.356-.144m.36-6.51q-.416 0-.71-.291T4 12.656t.291-.709t.707-.293t.709.29t.293.707t-.291.71t-.707.293m2.767-.115V5.423q0-.666.475-1.14t1.14-.475h5.232q.666 0 1.14.474t.475 1.141v8.116zm10.524-.176Q18 13.072 18 12.656t.291-.709t.707-.293t.709.29t.293.707t-.291.71t-.707.293t-.709-.291");
}

</style>
