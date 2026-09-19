<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="rs2v-0v7q"/><path class="aiur8zzfe"/><ellipse class="gfehtdbxi"/><ellipse class="rwfwf3pxy"/><path class="xt1ma59ky"/></g><path class="si5llx4yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bigo-live-lite" /></template>
<style>
.aiur8zzfe {
  d: path("M30.677 21.832c4.167 6.52 2.041 10.677-3.197 12.034m-8.341-11.377c.813.774 1.993.622 2.813.046c.16-1.546 1.387-1.492 1.598.1c.992-.02 2.03-.142 2.224.583c.113.776-.529 1.228-1.495 1.094c.045 1.554-.72 1.502-2.443 1.348c-.567.256-1.083.36-1.604.474m2.771-7.291c4.167 1.665 7.908 1.316 10.134-2.26");
}

.gfehtdbxi {
  cx: 24.902px;
  cy: 16.594px;
  rx: 0.928px;
  ry: 1.083px;
}

.rs2v-0v7q {
  d: path("M28.305 22.832c4.863-1.803 8.343-4.077 4.743-8.764c.248-9.448-15.366-11.25-19.281-.516c-.443 2.068-.3 6.526 1.237 10.105c.563 1.352.125 6.87-1.859 4.376c-.934-1.29-1.793-1.343-2.163-1.206c-1.78 3.348 2.82 6.2 3.825 6.22c2.51 2.974 4.649 2.604 6.464 2.741");
}

.rwfwf3pxy {
  cx: 31.347px;
  cy: 14.996px;
  rx: 0.773px;
  ry: 1.031px;
}

.si5llx4yx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.603 39.415h2.552m-7.842.015v4.038h1.818m1.729.032v-4.101m3.015 4.085v-4.069m2.984 2.034h1.191m.637-2.026h-1.829v4.053h1.829");
}

.xt1ma59ky {
  d: path("M21.107 34.592c5.716 11.63 11.807-15.401.438-5.25m11.245-3.88c9.383-5.943 2.228 11.078-1.546 6.857M25.52 6.255c-3.42-3.033-5.616-1.86-7.115 1.42c-6.43-1.377-6.245 3.984-4.64 5.877c-2.799 2.062-3.408 4.125.103 6.187c-1.351.64-2.74 2.911 1.135 4.537c-.983.804-2.305 1.552-.103 2.887M34.923 14.14h2.188m-1.094-1.276v2.48");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
