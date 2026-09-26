<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxub4xbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autopilot-32-filled" /></template>
<style>
.vxub4xbld {
  fill: currentColor;
  d: path("M25.985 4c4.69 0 6.8 5.876 3.181 8.858L16.726 23.11l-1.777 1.471a1 1 0 0 1-.084.063l-5.509 4.54a3.573 3.573 0 0 1-5.34-4.587l6.104-10.239l-6.32-3.642A3.6 3.6 0 0 1 5.598 4zM5.733 25.621a1.574 1.574 0 0 0 2.352 2.019l7.544-6.22l.22-.18a2.334 2.334 0 0 0-.341-3.829l-3.65-2.062zM5.598 6a1.6 1.6 0 0 0-.8 2.982l6.375 3.675l1.246-2.128c1.167-1.993-.263-4.502-2.572-4.515L7.413 6z");
}

</style>
