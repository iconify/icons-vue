<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rraypnbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-16-regular" /></template>
<style>
.rraypnbef {
  fill: currentColor;
  d: path("M11.12 7.963a.574.574 0 0 1 .76 0c.508.484 1.484 1.254 2.683 1.412c.24.031.437.212.437.438v2.11c0 2.839-2.784 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.174-.928 2.682-1.412M8 1a3 3 0 0 1 3 3v2c.957 0 1.756.673 1.952 1.571a6 6 0 0 1-.194-.16l-.187-.172l-.115-.098A1.58 1.58 0 0 0 10.763 7H5a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h2.462c.18.375.402.707.646 1H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2V4a3 3 0 0 1 3-3m0 1a2 2 0 0 0-2 2v2h4V4a2 2 0 0 0-2-2");
}

</style>
