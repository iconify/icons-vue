<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="askjv9bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dropdown-menu-rounded" /></template>
<style>
.askjv9bqs {
  fill: currentColor;
  d: path("m15.2 13.8l1.95-1.95q.25-.25.125-.55T16.8 11h-4.6q-.35 0-.475.3t.125.55l1.95 1.95q.3.3.7.3t.7-.3M8 19q-2.925 0-4.962-2.037T1 12t2.038-4.962T8 5h8q2.925 0 4.963 2.038T23 12t-2.037 4.963T16 19z");
}

</style>
