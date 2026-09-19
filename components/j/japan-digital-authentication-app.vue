<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-90rodjh"/><circle class="ejuzt7bht"/><path class="al0pajbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-digital-authentication-app" /></template>
<style>
.al0pajbfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.954a3.337 3.337 0 0 0-3.337 3.337v4.966h6.674V28.29A3.337 3.337 0 0 0 24 24.953");
}

.c-90rodjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5c1.616 0 5.019 4.162 6.511 4.78c1.493.618 6.842.082 7.985 1.224c1.142 1.143.606 6.492 1.224 7.985S44.5 22.385 44.5 24s-4.162 5.019-4.78 6.511c-.618 1.493-.082 6.842-1.224 7.985c-1.143 1.142-6.492.606-7.985 1.224S25.615 44.5 24 44.5s-5.019-4.162-6.511-4.78c-1.493-.618-6.842-.082-7.985-1.224c-1.142-1.143-.606-6.492-1.224-7.985S3.5 25.615 3.5 24s4.162-5.019 4.78-6.511c.618-1.493.082-6.842 1.224-7.985c1.143-1.142 6.492-.606 7.985-1.224S22.384 3.5 24 3.5");
}

.ejuzt7bht {
  cx: 24px;
  cy: 18.061px;
  r: 2.861px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
