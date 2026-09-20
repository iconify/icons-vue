<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-6d0sboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-16-filled" /></template>
<style>
.n-6d0sboi {
  fill: currentColor;
  d: path("M12.638 2.07c.808-.312 1.603.483 1.292 1.292l-3.846 9.998c-.348.906-1.653.834-1.9-.105l-1.06-4.024a.5.5 0 0 0-.356-.357L2.744 7.815c-.94-.247-1.01-1.552-.105-1.9z");
}

</style>
