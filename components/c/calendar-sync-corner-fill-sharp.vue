<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s39iunxhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sync-corner-fill-sharp" /></template>
<style>
.s39iunxhg {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5v10h4a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3Zm11 11h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.541.888h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
