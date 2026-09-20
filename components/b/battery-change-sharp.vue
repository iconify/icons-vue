<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpgmalrey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-change-sharp" /></template>
<style>
.cpgmalrey {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18zm4.75-4.35l1.425-1.4l-.95-.95q-.125-.125-.175-.262T12 14.75q0-.175.05-.312t.175-.263l.95-.95q.4-.4.613-.9t.212-1.05q0-.575-.212-1.087t-.613-.913l-.95-.95l-1.4 1.425l.925.925q.125.125.188.263t.062.312q0 .15-.062.288t-.188.262l-.925.95q-.4.4-.612.9T10 14.725t.212 1.088t.613.912z");
}

</style>
