<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xjonyos8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:incognito-16-filled" /></template>
<style>
.xjonyos8o {
  fill: currentColor;
  d: path("M12 8a3 3 0 1 1-2.958 3.5H6.958a3 3 0 1 1 0-1h2.084A3 3 0 0 1 12 8M4 9a2 2 0 1 0 0 4a2 2 0 0 0 0-4m8 0a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-1.117-7a1.5 1.5 0 0 1 1.342.83l1.528 3.057q.165.02.299.04l.39.057l.138.023h.003a.5.5 0 0 1-.166.986c-.018 0-.055-.009-.128-.02l-.377-.056A44 44 0 0 0 8 6.5a44 44 0 0 0-6.289.473c-.072.01-.126.02-.126.02h-.002a.5.5 0 0 1-.166-.986h.003l.138-.023l.39-.057l.3-.04l1.53-3.058A1.5 1.5 0 0 1 5.118 2z");
}

</style>
