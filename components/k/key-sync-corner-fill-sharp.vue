<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3yon6bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-sync-corner-fill-sharp" /></template>
<style>
.h3yon6bpe {
  fill: currentColor;
  d: path("m7.907 7.679l5.386-5.386a.999.999 0 1 1 1.414 1.414L14.414 4l1.293 1.293a1 1 0 0 1-.845 1.697a1.001 1.001 0 0 1-1.698.846l-1.292-1.293l-2.551 2.55a3.83 3.83 0 1 1-1.414-1.414m12.541 7.215h-.001A1 1 0 0 1 20 15h-3a1 1 0 0 1 0-2h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V11a1 1 0 0 1 2 0v3a1 1 0 0 1-.046.298l-.001.004a1 1 0 0 1-.505.592M15 17a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 13 20.577V21a1 1 0 0 1-2 0v-3a.997.997 0 0 1 1-1Z");
}

</style>
