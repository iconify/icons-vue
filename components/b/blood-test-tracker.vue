<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7jk9d0sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blood-test-tracker" /></template>
<style>
.s7jk9d0sd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.619 13.53a9.41 9.41 0 0 1-1.875 10.63L24 39.904L8.256 24.16A9.41 9.41 0 1 1 24 15.07A9.41 9.41 0 0 1 37.868 9.4L24 23.269l-7.426-7.427a2.353 2.353 0 0 0-3.327 3.327L24 29.922l17.196-17.196q.228.39.422.803z");
}

</style>
