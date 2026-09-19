<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqwxvsyev"/><path class="vr8ii5bkf"/><path class="vmzf-k8lb"/><path class="drbtk9b6c"/><path class="mmdj9wbbi"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:action-notch" /></template>
<style>
.drbtk9b6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.158 21.303a6.234 6.234 0 1 0-10.57-.038");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kqwxvsyev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.18 9.5h9.343m-.215 21.24l.004-2.171c.036-1.803 2.693-1.865 2.733 0v3.522");
}

.mmdj9wbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.121 19.264c.778-2.138-.737-4.682-3.284-4.68h0c-2.556 0-4.07 2.562-3.274 4.707m10.482 12.8v-1.704c0-1.377 2.412-1.499 2.412 0l.016 4.161c0 1.806-1.167 2.655-2.352 3.446c-.946.376-3.636.465-4.782.497c-2.285.065-2.955-.217-3.908-1.27l-5.28-6.712c-1.75-1.964.535-4.226 2.502-1.929l2.653 2.939");
}

.vmzf-k8lb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.306 31.519V18.295c0-2.269 3.023-2.269 3.023 0v9.84");
}

.vr8ii5bkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.34 28.136c-.001-.97.008-1.032-.01-1.591c-.06-1.82 2.993-1.887 2.974-.023c-.005.557-.014.612-.005 1.582l.01 2.652");
}

</style>
