<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhk-2c6jb"/><path class="c74s9mr1f"/><path class="ox-6f8b3g"/><path class="hnsrzsqtx"/><path class="g101o8q7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:halma" /></template>
<style>
.bhk-2c6jb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.28 13.12c-2 1.16-3.13 3.27-3.14 5.43c-.92.55-1.99.85-3.14.85s-2.22-.3-3.14-.85a6.24 6.24 0 0 1-3.14-5.43L24 2.5z");
}

.c74s9mr1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.86 18.55c0 1.07-.27 2.16-.84 3.15s-1.38 1.77-2.3 2.3a6.29 6.29 0 0 1-6.28 0L5.38 13.25l12.34-.13c0 2.33 1.26 4.35 3.14 5.43");
}

.g101o8q7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.62 34.75l-12.34.13c0-2.33-1.26-4.35-3.14-5.43c0-1.07.27-2.16.84-3.15s1.38-1.77 2.3-2.3a6.29 6.29 0 0 1 6.28 0z");
}

.hnsrzsqtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.28 34.88L24 45.5l-6.28-10.62c2-1.16 3.13-3.27 3.14-5.43c.92-.55 1.99-.85 3.14-.85s2.22.3 3.14.85a6.24 6.24 0 0 1 3.14 5.43m12.34-21.63L36.56 24a6.29 6.29 0 0 0-6.28 0c-.92-.53-1.73-1.31-2.3-2.3s-.84-2.08-.84-3.15a6.31 6.31 0 0 1 3.14-5.43z");
}

.ox-6f8b3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.86 29.45a6.31 6.31 0 0 1-3.14 5.43l-12.34-.13L11.44 24a6.29 6.29 0 0 0 6.28 0c.92.53 1.73 1.31 2.3 2.3s.84 2.08.84 3.15");
}

</style>
