<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path class="czuk_uaey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-bold-duotone" /></template>
<style>
.czuk_uaey {
  fill: currentColor;
  d: path("m17.1 18.122l3.666 3.666a.723.723 0 0 0 1.023-1.022L18.122 17.1a9 9 0 0 1-1.022 1.022");
}

.g-tqdrbyb {
  fill: currentColor;
  d: path("M20.313 11.157a9.157 9.157 0 1 1-18.313 0a9.157 9.157 0 0 1 18.313 0");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
