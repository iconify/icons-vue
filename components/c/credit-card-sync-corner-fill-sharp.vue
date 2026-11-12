<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt66_t3rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-sync-corner-fill-sharp" /></template>
<style>
.wt66_t3rw {
  fill: currentColor;
  d: path("M22 8H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Zm-12 2v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9Zm8 4h.748a3.47 3.47 0 0 0-4.854 1.447a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.541.888h-.001A1 1 0 0 1 21 16h-3a1 1 0 0 1 0-2m-4 7.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
