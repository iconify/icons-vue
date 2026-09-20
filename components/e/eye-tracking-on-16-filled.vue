<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="ojn8k41qh"/><path class="u9pd8e6ma"/><path class="lt537qu5r"/><path class="w7441fbaz"/><path class="yhhcncbdh"/><path class="kh-ji_blq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eye-tracking-on-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kh-ji_blq {
  d: path("M3.314 7.964a.5.5 0 0 0 .65-.278v.001l.005-.011l.028-.06c.027-.055.072-.137.136-.24a3.73 3.73 0 0 1 .64-.756C5.376 6.073 6.384 5.5 8 5.5c1.617 0 2.624.573 3.226 1.12c.305.277.512.553.64.757a2.752 2.752 0 0 1 .165.299s.244.452.655.288a.5.5 0 0 0 .278-.65c-.107-.223 0 0 0 0v-.002l-.002-.004l-.005-.01a1.809 1.809 0 0 0-.06-.129a3.783 3.783 0 0 0-.186-.327a4.733 4.733 0 0 0-.812-.962c-.774-.703-2.017-1.38-3.9-1.38c-1.882 0-3.125.677-3.898 1.38a4.73 4.73 0 0 0-.813.962a3.753 3.753 0 0 0-.246.456l-.004.01l-.002.005v.001a.5.5 0 0 0 .278.65z");
  fill: currentColor;
}

.lt537qu5r {
  d: path("M12 2a2 2 0 0 1 2 2v1.5a.5.5 0 0 1-1 0V4a1 1 0 0 0-1-1h-1.5a.5.5 0 0 1 0-1H12z");
  fill: currentColor;
}

.ojn8k41qh {
  d: path("M2 4a2 2 0 0 1 2-2h1.5a.5.5 0 0 1 0 1H4a1 1 0 0 0-1 1v1.5a.5.5 0 0 1-1 0V4z");
  fill: currentColor;
}

.u9pd8e6ma {
  d: path("M2 12a2 2 0 0 0 2 2h1.5a.5.5 0 0 0 0-1H4a1 1 0 0 1-1-1v-1.5a.5.5 0 0 0-1 0V12z");
  fill: currentColor;
}

.w7441fbaz {
  d: path("M14 12a2 2 0 0 1-2 2h-1.5a.5.5 0 0 1 0-1H12a1 1 0 0 0 1-1v-1.5a.5.5 0 0 1 1 0V12z");
  fill: currentColor;
}

.yhhcncbdh {
  d: path("M5.5 9a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0z");
  fill: currentColor;
}

</style>
