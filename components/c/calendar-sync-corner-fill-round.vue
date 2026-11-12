<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6xcbebns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sync-corner-fill-round" /></template>
<style>
.p6xcbebns {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1.099a5.01 5.01 0 0 1 3.607 2.954c.261.616.395 1.278.393 1.947a1 1 0 0 1-1 1H5v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H8a5 5 0 0 1-5-5V9a5.01 5.01 0 0 1 4-4.901Zm11 11h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.541.888h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
