<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nb38wbbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:black-medium-small-square" /></template>
<style>
.nb38wbbdj {
  fill: var(--svg-color--333, #333);
  d: path("M12 12h40v40H12z");
}

</style>
