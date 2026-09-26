<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-pxawmvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-cursor-sharp-fill" /></template>
<style>
.c-pxawmvx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM6.2952 7.5961L9.8298 18.6891C10.1059 19.5556 11.3014 19.6336 11.6878 18.8105L14.0107 13.8623L18.8253 11.8667C19.6804 11.5122 19.6364 10.2862 18.758 9.994L8.4883 6.5781L7.4964 6.3238C6.7352 6.1287 6.0567 6.8474 6.2952 7.5961Z");
}

</style>
