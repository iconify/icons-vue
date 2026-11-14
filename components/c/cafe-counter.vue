<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhvx1g9eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cafe-counter" /></template>
<style>
.dhvx1g9eh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 3.25h.5q1.036 0 1.768.732T10 5.75v.5q0 .541-.2 1h.2q.065 0 .128.011q.064.011.124.033q.061.022.117.053q.057.032.106.073q.05.041.093.09t.075.104t.056.115q.024.061.036.124l.88 4.397h1.969q-.334-.708-.334-1.75V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T14 6.25h5q.116 0 .227.035t.206.103t.165.16t.109.202H20q2 0 2 2t-2 2h-.255q-.036.879-.329 1.5h.334q1.036 0 1.768.732t.732 1.768v4q0 1.036-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5v-4q0-1.036.732-1.768q.149-.148.31-.267l.973-4.862q.012-.063.036-.124q.023-.06.056-.115t.075-.104t.093-.09q.049-.041.106-.073t.117-.053t.124-.033t.128-.011h.127q-.127-.436-.127-1v-.5q0-2.5 2.5-2.5m12.75 6H20q.5 0 .5-.5t-.5-.5h-.25zm-10.365-.5h-4.27l-.7 3.5h5.67z");
}

</style>
