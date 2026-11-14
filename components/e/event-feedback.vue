<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh02ufrob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:event-feedback" /></template>
<style>
.vh02ufrob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.512 18.473l-2.778 2.35q-.067.056-.146.096t-.164.061q-.086.02-.174.02t-.174-.02q-.072-.018-.139-.048t-.127-.074t-.11-.098t-.089-.117t-.064-.132t-.038-.142q-.011-.073-.008-.147t.019-.146l1.186-4.981q-2.113-4.257.189-8.485q2.372-4.353 7.311-4.789q4.938-.436 8.036 3.436t1.588 8.594t-6.278 6.08q-4.456 1.269-8.04-1.458m6.796-10.658q-.383-.841-1.307-.841t-1.308.842l-.264.581q-.18.397-.615.436l-.558.051q-.866.079-1.135.906t.387 1.401l.37.324q.315.275.246.688L9 12.938q-.15.898.603 1.411q.752.512 1.533.044l.478-.287q.386-.232.772 0l.478.287q.781.468 1.533-.044q.753-.513.603-1.41l-.123-.737q-.069-.413.245-.688l.372-.324q.655-.573.386-1.401q-.269-.827-1.135-.906l-.558-.051q-.435-.039-.615-.436z");
}

</style>
