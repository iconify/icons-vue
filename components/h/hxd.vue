<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="kysm70bca"><path class="lxsk2_iux"/><path class="i6ebjftfx"/><path class="tea5bvbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hxd" /></template>
<style>
.i6ebjftfx {
  d: path("M14.813 9.75H4.688v1.687h14.625V5.531L14.813 3zm4.5 4.5v-1.687H4.688v6.187l4.5 2.25v-6.75z");
}

.kysm70bca {
  fill: var(--svg-color--f8c007, #f8c007);
}

.lxsk2_iux {
  d: path("M4.688 5.531v3.094h4.5V3z");
}

.tea5bvbbv {
  d: path("M19.312 15.375h-4.5V21l4.5-2.531z");
}

</style>
