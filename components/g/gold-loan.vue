<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq3-9mgan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gold-loan" /></template>
<style>
.jq3-9mgan {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.674 2.25h3.652q1.01-.001 1.682.755l.553.622q.624.701.485 1.63q-.138.929-.939 1.418l-1.446.883q1.651.501 2.966 1.815q1.572 1.573 1.98 3.627H17q-2.071 0-3.536 1.464Q12 15.929 12 18q0 1.875 1.2 3.253q-1.247.497-2.7.497q-3.003 0-5.127-2.123T3.25 14.5t2.123-5.127q1.315-1.314 2.966-1.815l-1.446-.883q-.801-.489-.939-1.418q-.139-.929.486-1.631l.551-.621q.672-.756 1.683-.755m8.326 12q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q.174 0 .318.03q-.351.954-.986 1.79Q16 18.576 16 18q0-1 1-1");
}

</style>
