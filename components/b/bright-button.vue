<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nenjtj0di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bright-button" /></template>
<style>
.nenjtj0di {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M20 6a2 2 0 0 1-4 0V2a2 2 0 0 1 4 0zm0 28a2 2 0 0 1-4 0v-4a2 2 0 0 1 4 0zM6 16a2 2 0 0 1 0 4H2a2 2 0 0 1 0-4zm28 0a2 2 0 0 1 0 4h-4a2 2 0 0 1 0-4zM8.101 25.071a2 2 0 0 1 2.828 2.828l-2.828 2.829A2 2 0 1 1 5.273 27.9zM27.899 5.272a2 2 0 0 1 2.828 2.829l-2.828 2.828A2 2 0 1 1 25.071 8.1zm-2.828 22.627a2 2 0 0 1 2.828-2.828l2.829 2.828a2 2 0 1 1-2.828 2.828zM18 9a9 9 0 1 0 0 18a9 9 0 0 0 0-18m0 14a5 5 0 1 1 0-10a5 5 0 0 1 0 10M5.272 8.101a2 2 0 0 1 2.829-2.828l2.828 2.828A2 2 0 1 1 8.1 10.929z");
}

</style>
