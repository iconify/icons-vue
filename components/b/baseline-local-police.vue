<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlv442bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-local-police" /></template>
<style>
.zlv442bvv {
  fill: currentColor;
  d: path("M12 1L3 5v6c0 5.55 3.84 10.74 9 12c5.16-1.26 9-6.45 9-12V5zm2.5 11.59l.9 3.88l-3.4-2.05l-3.4 2.05l.9-3.87l-3-2.59l3.96-.34L12 6.02l1.54 3.64l3.96.34z");
}

</style>
