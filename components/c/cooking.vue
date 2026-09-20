<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x4xw_dbeb"/><circle class="hq_j6rw5o"/><path class="v6w7s6bjf"/><circle class="td1lnp0zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cooking" /></template>
<style>
.hq_j6rw5o {
  cx: 15px;
  cy: 15px;
  r: 12px;
  fill: var(--svg-color--66757f, #66757f);
}

.td1lnp0zf {
  cx: 13px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.v6w7s6bjf {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M16 25c4.863-1.533 4-5 4-9s4.001-6.708.334-9.75c-2.177-1.806-6.75-2.417-8.875-1.625C9.506 5.352 7 6.833 7 9.833s-.058 2.927-1.708 5.625C2.667 19.75 9.125 27.167 16 25");
}

.x4xw_dbeb {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M34.238 27.931c-.704-.703-3.857-2.661-6.935-4.364A14.9 14.9 0 0 0 30 15c0-8.284-6.716-15-15-15C6.715 0 0 6.716 0 15s6.715 15 15 15c3.159 0 6.086-.981 8.504-2.649c1.705 3.081 3.666 6.24 4.37 6.944C29.288 35.709 31 36.002 32 36c1.177-.002 4.055-2.881 4-4c-.049-.999-.348-2.655-1.762-4.069");
}

</style>
