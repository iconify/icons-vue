<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaoyf82ot"/><path class="vmj_u5b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-bold-duotone" /></template>
<style>
.vmj_u5b4k {
  fill: currentColor;
  d: path("M12.7705 20C12.7705 20.4142 12.4347 20.75 12.0205 20.75C11.6063 20.75 11.2705 20.4142 11.2705 20L11.2705 4C11.2705 3.58579 11.6063 3.25 12.0205 3.25C12.4347 3.25005 12.7705 3.58582 12.7705 4L12.7705 20Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yaoyf82ot {
  fill: currentColor;
  d: path("M20 11.25C20.4142 11.25 20.75 11.5858 20.75 12C20.75 12.4142 20.4142 12.75 20 12.75L4 12.75C3.58579 12.75 3.25 12.4142 3.25 12C3.25 11.5858 3.58579 11.25 4 11.25L20 11.25Z");
}

</style>
