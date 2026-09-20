<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpo1abcjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:key-vertical-outline-rounded" /></template>
<style>
.lpo1abcjo {
  fill: currentColor;
  d: path("M11.626 6.126q.357-.357.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357T11.269 7t.357-.874M7.5 7q0-2.077 1.462-3.538T12.5 2t3.539 1.462T17.5 7q0 1.54-.835 2.778q-.834 1.238-2.165 1.807v8.875q0 .161-.056.3q-.055.14-.186.27l-1.192 1.193q-.131.13-.268.184q-.136.052-.298.052t-.298-.052t-.267-.184l-2.098-2.117q-.106-.106-.171-.243q-.066-.136-.072-.272q-.005-.137.035-.274q.04-.136.127-.267l.879-1.165l-.998-1.368q-.081-.105-.112-.217t-.03-.242t.04-.245t.102-.22l.863-1.295v-2.713q-1.311-.57-2.156-1.807T7.5 7m1 0q0 1.477.889 2.52t2.111 1.336v3.76l-.967 1.43q0-.019-.003-.01q-.003.01.003.01l1.333 1.858l-1.222 1.621h.01h-.01l1.856 1.856v-.003v.003l1-1h.003h-.003v-9.525q1.223-.292 2.112-1.336T16.5 7q0-1.65-1.175-2.825T12.5 3T9.675 4.175T8.5 7");
}

</style>
