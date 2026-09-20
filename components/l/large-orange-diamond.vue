<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9ub_6f4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:large-orange-diamond" /></template>
<style>
.r9ub_6f4e {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M1.061 19.062a1.506 1.506 0 0 1 0-2.122L16.94 1.061a1.506 1.506 0 0 1 2.122 0L34.94 16.94a1.505 1.505 0 0 1 0 2.121L19.062 34.939a1.506 1.506 0 0 1-2.122 0z");
}

</style>
