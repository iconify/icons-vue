<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k_z_r3y3f"/><path class="rh5bd48nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-pump-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k_z_r3y3f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

.rh5bd48nz {
  d: path("M6 11a6 6 0 1 1 12 0a6 6 0 0 1-12 0m5.644-1.522c.861-.861 2.343-1.078 3.509-.94A3.99 3.99 0 0 0 12 7c-.108 0-.2.172-.243.252c-.32.6-.324 1.587-.113 2.226m-1.166 1.878c-.861-.861-1.078-2.343-.94-3.509A3.99 3.99 0 0 0 8 11c0 .108.172.2.252.243c.6.32 1.587.324 2.226.113m3.044-.712c.861.861 1.078 2.343.94 3.509A3.99 3.99 0 0 0 16 11c0-.108-.172-.2-.252-.243c-.6-.32-1.587-.324-2.226-.113m-4.675 2.818A3.99 3.99 0 0 0 12 15c.108 0 .2-.172.243-.252c.32-.6.324-1.587.113-2.226c-.861.861-2.343 1.078-3.509.94M8 21a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm10 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
