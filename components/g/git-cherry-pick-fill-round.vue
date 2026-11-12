<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe56prbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-cherry-pick-fill-round" /></template>
<style>
.xe56prbzw {
  fill: currentColor;
  d: path("M11.473 5.024a5.95 5.95 0 0 1 1.861-1.589A5.5 5.5 0 0 1 16 2.75c1.994 0 3.738 1.055 4.832 2.695a1 1 0 0 1-.125 1.262c-.319.32-.677.599-1.05.854c-.588.399-1.215.738-1.871 1.01c1.355 1.909 2.06 4.268 2.191 6.592a3 3 0 1 1-2.003.017c-.143-2.236-.908-4.543-2.438-6.218c-.692-.107-1.36-.381-1.983-.693a9.4 9.4 0 0 1-1.924-1.251c-1.626.16-2.927 1.357-3.797 2.662a10.7 10.7 0 0 0-1.341 2.93c-.247.837-.402 1.7-.463 2.571a3 3 0 1 1-2.003-.019c.139-2.308.857-4.662 2.143-6.592c.666-.998 1.496-1.894 2.507-2.55c.842-.545 1.796-.906 2.798-.996");
}

</style>
