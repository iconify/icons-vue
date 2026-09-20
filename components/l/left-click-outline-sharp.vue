<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiimo-buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:left-click-outline-sharp" /></template>
<style>
.eiimo-buh {
  fill: currentColor;
  d: path("M11.412 16.962q-1.881-.24-3.147-1.639Q7 13.925 7 12q0-2.077 1.462-3.538T12 7q1.925 0 3.323 1.256q1.398 1.255 1.639 3.136l-1.081-.317q-.325-1.35-1.39-2.212Q13.425 8 12 8q-1.65 0-2.825 1.175T8 12q0 1.425.872 2.5t2.203 1.4zm8.344 3.827l-4.794-4.814l-.923 2.794L12 12l6.77 2.039l-2.795.923l4.814 4.794z");
}

</style>
