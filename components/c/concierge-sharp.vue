<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h00xbr7au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:concierge-sharp" /></template>
<style>
.h00xbr7au {
  fill: currentColor;
  d: path("M2.039 11.923h3V3.769h-3zm4 0h2.378l7.352-2.711V7.616h-3l-2.596.925l-.311-.752l2.869-.943h7.923V5.27l-7-2.307l-7.615 2.225zM11 21h11v-1H11zm1-2.384h9q0-1.737-1.153-3.01q-1.153-1.271-2.847-1.448v-.914h-1v.914q-1.7.177-2.85 1.449T12 18.616");
}

</style>
