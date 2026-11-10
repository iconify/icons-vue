<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fageo89fr"/><path class="h3rvgndql"/><path class="tbqp1f_7k"/><path class="xvbw140tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kuwo-player" /></template>
<style>
.fageo89fr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.381 10.777c1.251 1.251.366 2.406-.29 3.037c-.6.574-1.216 1.712-.449 2.637c.632.761 1.804 1.404 3.153.055c1.38-1.38.532-2.823-.237-3.574l-4.402-4.3c-.714-.698-.422-1.524.74-1.78c1.098-.242 1.74-.735 2.324-1.265c.618 2.688-1.292 3.352-2.573 3.366");
}

.h3rvgndql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.881 9.068c6.707-2.13 15.684-1.023 20.041 3.315c5.841 5.814 5.832 19.873-.016 25.68s-19.988 5.798-25.828-.016c-4.546-4.525-5.549-14.045-3.013-20.78");
}

.tbqp1f_7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.65 27.182l-2.052-1.978l2.052-1.975c1.705-1.642 1.322-4.35-.327-6.048a4.3 4.3 0 0 0-3.014-1.303c-1.14-.02-2.257.395-3.327 1.423l-5.207 4.997c-.822.795-1.687 1.851-1.687 2.907s.865 2.113 1.687 2.907l5.207 4.998c1.958 1.88 4.692 1.818 6.34.12c1.65-1.699 2.033-4.406.328-6.049");
}

.xvbw140tj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.651 29.912v.546a4.035 4.035 0 0 1-4.026 4.044h-.466a4.035 4.035 0 0 1-4.043-4.027V19.921a4.035 4.035 0 0 1 4.026-4.044h.467a4.035 4.035 0 0 1 4.042 4.027v.594");
}

</style>
