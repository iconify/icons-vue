<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t61_uz5gp"/><path class="uypl0hb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cangjie" /></template>
<style>
.t61_uz5gp {
  fill: var(--svg-color--0673fe, #0673fe);
  d: path("M6 5.333c3.311.207 6.553.437 9.833.854l1.132.14q1.35.168 2.702.34l.333 1q-1.204.44-2.417.854l-.669.25c-2.354.788-3.464.46-6.247.229v14l4-.333c1.012.226 1.811.435 2.75.812l.668.246q.794.294 1.582.608v1q-2.277.288-4.554.57l-1.545.194q-1.117.14-2.235.278l-.687.088c-1.582.192-3.027.204-4.646.204z");
}

.uypl0hb7w {
  fill: var(--svg-color--00f196, #00f196);
  d: path("M26.333 7.667v16.666c-2.628.376-2.628.376-3.643.037l-.656-.218l-.659-.235l-.682-.22c-.649-.223-.649-.223-1.693-.697l-.333-1h2.666V10h-2.666L19 9a22 22 0 0 1 2.375-.917l.659-.235l.656-.218l.591-.197c.719-.1.719-.1 3.052.234");
}

</style>
