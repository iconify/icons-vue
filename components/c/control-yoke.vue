<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czxw-ubqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:control-yoke" /></template>
<style>
.czxw-ubqn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.75q0-2.5-2.5-2.5t-2.5 2.5v5q0 2.112 1.785 2.44q.327 3.06 3.715 3.06h3.5v6.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25h3.5q3.409 0 3.719-3.099q.585-.17 1.049-.633q.732-.732.732-1.768v-5q0-1.036-.732-1.768T19.25 2.25t-1.768.732t-.732 1.768v5q0 1.036.732 1.768q.431.431.967.608q-.287 1.624-2.199 1.624h-8.5q-1.885 0-2.191-1.579Q7.25 11.806 7.25 9.75z");
}

</style>
