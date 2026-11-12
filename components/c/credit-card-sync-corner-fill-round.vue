<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i30jhubgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-sync-corner-fill-round" /></template>
<style>
.i30jhubgc {
  fill: currentColor;
  d: path("M21.901 8H2.099A5.01 5.01 0 0 1 7 4h10a5.01 5.01 0 0 1 4.901 4M10 10v9a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5v-5Zm8 4h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.541.888h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
