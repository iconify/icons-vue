<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="w3h89llez"><path class="enttlfywx"/><path class="iy-qv2bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gymnet" /></template>
<style>
.enttlfywx {
  d: path("M12 11.438a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5m8.145-8.437c-.27 4.533-4.601 8.33-6.727 9.668A8.81 8.81 0 0 0 20.814 11c.54-3.465-.225-6.778-.675-7.998z");
}

.iy-qv2bib {
  d: path("M20.144 12.67C9.384 16.662 4.902 7.888 4.002 3c-3.695 11.001 3.7 16.333 8.07 17.998c4.838-1.867 7.397-6.333 8.072-8.33");
}

.w3h89llez {
  fill: var(--svg-color--2f6eb6, #2f6eb6);
}

</style>
