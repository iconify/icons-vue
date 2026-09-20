<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iwk1lccse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-link-20-filled" /></template>
<style>
.iwk1lccse {
  fill: currentColor;
  d: path("M12.5 3a2.5 2.5 0 0 0 0 5h.5a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3h.5a.5.5 0 0 0 0-1zM16 3a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H16a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-4 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5m-3 0c0-.537.12-1.045.337-1.5H4.5a2.5 2.5 0 0 0-2.485 2.223L10 10.92L13.264 9H12.5A3.5 3.5 0 0 1 9 5.5M16.5 9h-1.265l-4.981 2.931a.5.5 0 0 1-.507 0L2 7.373V14.5A2.5 2.5 0 0 0 4.5 17h11a2.5 2.5 0 0 0 2.5-2.5V8.663A3.5 3.5 0 0 1 16.5 9");
}

</style>
