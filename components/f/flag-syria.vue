<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e-rrrkuug"/><path class="ckvc8w1cl"/><path class="kpv3-4c9x"/><path class="kv7cx9bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-syria" /></template>
<style>
.ckvc8w1cl {
  fill: var(--svg-color--007a3d, #007a3d);
  d: path("M32 5H4C1.791 5 0 6.94 0 9.333v4.333h36V9.333C36 6.94 34.209 5 32 5");
}

.e-rrrkuug {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.666h36v8.666H0Z");
}

.kpv3-4c9x {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 30.999H4c-2.209 0-4-1.94-4-4.333v-4.333h36v4.333c0 2.393-1.791 4.333-4 4.333");
}

.kv7cx9bur {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("m24.977 18.48l-.633 1.945L26 19.223l1.656 1.202l-.633-1.946l1.656-1.2h-2.047L26 15.332l-.632 1.945h-2.047zm-8 0l-.633 1.945L18 19.223l1.656 1.202l-.633-1.946l1.656-1.2h-2.047L18 15.332l-.632 1.945h-2.047zm-8 0l-.633 1.945L10 19.223l1.656 1.202l-.633-1.946l1.656-1.2h-2.047L10 15.332l-.632 1.945H7.321Z");
}

</style>
