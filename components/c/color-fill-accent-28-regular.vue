<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a6zgpz0gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-fill-accent-28-regular" /></template>
<style>
.a6zgpz0gz {
  fill: currentColor;
  d: path("M16.512 17.75a3 3 0 0 0-.012.25a3.5 3.5 0 0 0 6.973.438c.479.456.777 1.1.777 1.812v1.5a2.5 2.5 0 0 1-2.5 2.5H6.25a2.5 2.5 0 0 1-2.5-2.5v-1.5a2.5 2.5 0 0 1 2.5-2.5h1.011l1.102 1.102a3.75 3.75 0 0 0 5.303 0l1.101-1.102z");
}

</style>
