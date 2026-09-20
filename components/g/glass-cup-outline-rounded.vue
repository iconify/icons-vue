<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmdqq5bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:glass-cup-outline-rounded" /></template>
<style>
.rmdqq5bie {
  fill: currentColor;
  d: path("M6.975 22q-.775 0-1.337-.5T5 20.225l-1.75-16q-.1-.875.488-1.55T5.225 2h13.55q.9 0 1.488.675t.487 1.55l-1.75 16q-.075.775-.637 1.275t-1.338.5zm-.2-4L7 20h10l.225-2zm-.2-2H17.45l1.3-12H5.25zm.2 4h10.45z");
}

</style>
