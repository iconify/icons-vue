<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t6t0p4qui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bookcatalogue" /></template>
<style>
.t6t0p4qui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.3 42.5h34.1m-34-2l7-.2l-.5-34.7l-6.3-.1Zm8.6-27l-.3 26.3l6.5-.2l.8-25.9Zm9-5.6l-1.4 32.2l8.7-.1L33 8.4Zm10 6.3l-1.5 26.3l7.8.1l1.4-26.3Zm1 0a8.5 8.5 0 0 1 5.7-3.7M12.9 5.6L14.8 9l.1 4.6m-1.5 26.7l1.3-.5");
}

</style>
