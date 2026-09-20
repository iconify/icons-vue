<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":182};
const content = `<path class="e6i3r_bdz"/><path class="rv6_lbblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:akka" /></template>
<style>
.e6i3r_bdz {
  fill: var(--svg-color--0b5567, #0b5567);
  d: path("M216.358 174.771c38.778 31.001 63.622-61.57 1.836-78.636c-51.848-14.366-104.02 10.262-156.3 67.727c0 0 96.567-35.322 154.464 10.91");
}

.rv6_lbblq {
  fill: var(--svg-color--15a9ce, #15a9ce);
  d: path("M62.758 163.105c37.158-38.562 98.943-81.552 156.516-65.674c13.394 3.78 22.9 11.558 29.057 20.847L193.89 8.425c-7.778-12.422-27.653-9.83-38.887-.324L11.126 128.648c-13.07 11.234-13.826 31.217-1.729 43.315c10.694 10.694 27.653 11.666 39.427 2.16z");
}

</style>
