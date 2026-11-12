<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="r9znqobzq"/><path class="czuk_uaey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-zoom-in-bold-duotone" /></template>
<style>
.aygw_60rm {
  fill: currentColor;
  d: path("M11.157 20.313a9.157 9.157 0 1 0 0-18.313a9.157 9.157 0 0 0 0 18.313");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.czuk_uaey {
  fill: currentColor;
  d: path("m17.1 18.122l3.666 3.666a.723.723 0 0 0 1.023-1.022L18.122 17.1a9 9 0 0 1-1.022 1.022");
}

.r9znqobzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.157 8.024c.399 0 .722.324.722.723v1.687h1.687a.723.723 0 1 1 0 1.446H11.88v1.687a.723.723 0 1 1-1.445 0V11.88H8.747a.723.723 0 1 1 0-1.446h1.687V8.747c0-.399.323-.723.723-.723");
}

</style>
