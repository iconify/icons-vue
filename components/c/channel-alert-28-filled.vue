<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jnzm_0buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-alert-28-filled" /></template>
<style>
.jnzm_0buw {
  fill: currentColor;
  d: path("M3 7.168a1.75 1.75 0 1 0 1.5 3.163A1.75 1.75 0 0 0 3 7.168m.168-1.106A2.75 2.75 0 1 1 3 11.397v9.353A4.25 4.25 0 0 0 7.25 25h7.25a7.47 7.47 0 0 1-1.5-4.5c0-1.47.423-2.842 1.155-4H9.75a.75.75 0 0 1 0-1.5h5.65a7.47 7.47 0 0 1 5.1-2c1.688 0 3.247.558 4.5 1.5V7.25A4.25 4.25 0 0 0 20.75 3H7.25a4.25 4.25 0 0 0-4.082 3.062M9.75 11h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5M27 20.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0M20.5 16a2.5 2.5 0 0 0-2.5 2.5v2.793l-.854.853A.5.5 0 0 0 17.5 23h6a.5.5 0 0 0 .354-.854L23 21.293V18.5a2.5 2.5 0 0 0-2.5-2.5m-1.415 8a1.5 1.5 0 0 0 2.83 0z");
}

</style>
