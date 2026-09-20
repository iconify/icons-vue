<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><path class="h8qm8xbqz"/><path class="g3e-9yb-m"/><path class="i1_4sq5pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-stuck-out-tongue-and-closed-eyes" /></template>
<style>
.g3e-9yb-m {
  fill: var(--svg-color--e8596e, #e8596e);
  d: path("m18.545 23.604l-1.091-.005c-3.216-.074-5.454-.596-5.454-.596v6.961c0 3 2 6 6 6s6-3 6-6v-6.92a28.7 28.7 0 0 1-5.455.56");
}

.h8qm8xbqz {
  fill: var(--svg-color--66471b, #66471b);
  d: path("M6.001 20a1 1 0 0 1-.601-1.799c.143-.107 2.951-2.183 6.856-2.933C9.781 14.027 7.034 14 6.999 14A1.001 1.001 0 0 1 7 12c.221 0 5.452.038 8.707 3.293A1 1 0 0 1 15 17c-4.613 0-8.363 2.772-8.4 2.8a1 1 0 0 1-.599.2m23.998-.001a1 1 0 0 1-.598-.198C29.363 19.772 25.59 17 21 17a.999.999 0 0 1-.707-1.707C23.549 12.038 28.779 12 29 12a1 1 0 0 1 .002 2c-.036 0-2.783.027-5.258 1.268c3.905.75 6.713 2.825 6.855 2.933a1 1 0 0 1-.6 1.798M7 21.263c0 3.964 4.596 9 11 9s11-5 11-9c0 0-10.333 2.756-22 0");
}

.i1_4sq5pn {
  fill: var(--svg-color--dd2f45, #dd2f45);
  d: path("M18 31.844a.545.545 0 0 0 .545-.545v-7.694l-1.091-.005v7.699a.546.546 0 0 0 .546.545");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

</style>
