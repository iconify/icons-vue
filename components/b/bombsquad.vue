<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd30d7b9m"/><g class="y9tr6bcfx"><path class="kcq1zebgk"/><path class="imql_lixs"/></g><path class="xqc22cc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bombsquad" /></template>
<style>
.imql_lixs {
  d: path("M29.249 8.07c2.333-6.49 8.05-2.954 10.52 1.328M19.046 19.461v2.461m8.299-3.314l.747 2.427");
}

.kcq1zebgk {
  d: path("m21.038 12.297l1.625-4.933c4.781-.092 8.258.792 12.337 3.35l-1.118 4.843");
}

.wd30d7b9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.996 12.409C29.498 10.804 37.69 16.4 39.294 24.91s-3.989 16.71-12.49 18.314h-.001c-8.502 1.606-16.694-3.991-18.298-12.5s3.988-16.71 12.49-18.315");
}

.xqc22cc1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.35 26.79c.664 3.359-1.123 6.728-4.557 8.592c-3.433 1.864-7.87 1.873-11.315.023s-5.252-5.21-4.609-8.573m19.804-.204h1.59m-20.615.25l-1.593-.428");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
