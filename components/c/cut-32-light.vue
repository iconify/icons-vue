<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ct47v-ttu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cut-32-light" /></template>
<style>
.ct47v-ttu {
  fill: currentColor;
  d: path("M8.225 2.083a.5.5 0 0 1 .629.064l.063.078l11.488 17.428a5.5 5.5 0 1 1-.835.55L16 14.785l-3.57 5.418a5.5 5.5 0 1 1-.835-.55l3.806-5.776L8.083 2.776l-.048-.09a.5.5 0 0 1 .19-.603M9 20a4.5 4.5 0 1 0 2.7.9l-.223-.157A4.5 4.5 0 0 0 9 20m14 0c-.916 0-1.767.273-2.477.742l-.223.158A4.5 4.5 0 1 0 23 20m.146-17.853a.5.5 0 0 1 .819.539l-.048.09l-6.72 10.194l-.6-.908l6.486-9.837z");
}

</style>
