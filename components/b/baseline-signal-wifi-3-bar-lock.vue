<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv3e82bxs"/><path class="j0kk0-b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-wifi-3-bar-lock" /></template>
<style>
.dv3e82bxs {
  fill: currentColor;
  d: path("M12 3C5.3 3 .8 6.7.4 7l3.2 3.9L12 21.5l3.5-4.3v-2.6c0-2.2 1.4-4 3.3-4.7c.3-.1.5-.2.8-.2c.3-.1.6-.1.9-.1c.4 0 .7 0 1 .1L23.6 7c-.4-.3-4.9-4-11.6-4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j0kk0-b9h {
  fill: currentColor;
  d: path("M23 16v-1.5c0-1.4-1.1-2.5-2.5-2.5S18 13.1 18 14.5V16c-.5 0-1 .5-1 1v4c0 .5.5 1 1 1h5c.5 0 1-.5 1-1v-4c0-.5-.5-1-1-1m-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5zm-10 5.5l3.5-4.3v-2.6c0-2.2 1.4-4 3.3-4.7C17.3 9 14.9 8 12 8c-4.8 0-8 2.6-8.5 2.9");
}

</style>
