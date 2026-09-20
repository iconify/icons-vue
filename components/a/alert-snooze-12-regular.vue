<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fw-v5ab1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-snooze-12-regular" /></template>
<style>
.fw-v5ab1x {
  fill: currentColor;
  d: path("M7.5 1a.5.5 0 0 0 0 1h2L7.1 5.2a.5.5 0 0 0 .4.8h3a.5.5 0 0 0 0-1h-2l2.4-3.2a.5.5 0 0 0-.4-.8zm2.481 6a.498.498 0 0 0-.428.723L9.69 8H2.309l.638-1.277A.5.5 0 0 0 3 6.5V5a3 3 0 0 1 2.57-2.97a.5.5 0 1 0-.14-.99A4 4 0 0 0 2 5v1.382l-.947 1.894A.5.5 0 0 0 1.5 9H4a2 2 0 0 0 4 0h2.5a.5.5 0 0 0 .447-.724l-.5-1a.5.5 0 0 0-.43-.276zM5 9h2a1 1 0 1 1-2 0");
}

</style>
