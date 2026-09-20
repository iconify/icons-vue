<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xlgjvuirl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-down-48-regular" /></template>
<style>
.xlgjvuirl {
  fill: currentColor;
  d: path("M7.25 12.5a1.25 1.25 0 1 1 0-2.5h18.5A7.25 7.25 0 0 1 33 17.25v18.168l6.854-7.04a1.25 1.25 0 0 1 1.792 1.744l-9.25 9.5a1.25 1.25 0 0 1-1.792 0l-9.25-9.5a1.25 1.25 0 0 1 1.792-1.744l7.354 7.553V17.25a4.75 4.75 0 0 0-4.75-4.75z");
}

</style>
