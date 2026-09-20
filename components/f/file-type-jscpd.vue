<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="skdjg5zcs"/><path class="od796ga4t"/><path class="p0lury97l"/><path class="extk5lbjq"/><path class="prb8_sqth"/><path class="vg9qq6x-x"/><path class="kc91_yb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jscpd" /></template>
<style>
.extk5lbjq {
  fill: var(--svg-color--b200b2, #b200b2);
  d: path("M8.931 15.641h15.733v1.105H8.931z");
}

.kc91_yb0p {
  fill: var(--svg-color--0d0, #0d0);
  d: path("M6.265 25.582h17.067v1.105H6.265z");
}

.od796ga4t {
  fill: var(--svg-color--f0f0f0, #f0f0f0);
  d: path("M3.6 10.119h24.8v18.225H3.6z");
}

.p0lury97l {
  fill: var(--svg-color--007bff, #007bff);
  d: path("M5.731 12.88h10.4v1.105h-10.4z");
}

.prb8_sqth {
  fill: var(--svg-color--ffaa56, #ffaa56);
  d: path("M9.731 18.955h12.267v1.105H9.731z");
}

.skdjg5zcs {
  fill: var(--svg-color--666, #666);
  d: path("m8.845 8.462l3.181-5.778L10.867 2L7.923 7.349L4.704 2.062l-1.128.737l3.449 5.663H2V30h28V8.462z");
}

.vg9qq6x-x {
  fill: var(--svg-color--b2b2b2, #b2b2b2);
  d: path("M6.798 22.268h12.267v1.105H6.798z");
}

</style>
