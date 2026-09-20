<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_zri2ibe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blender-outline-sharp" /></template>
<style>
.d_zri2ibe {
  fill: currentColor;
  d: path("M6 22v-4.75l1.85-2.1L7.225 11H3V3h7V2h4v1h3.975L16.15 15.15l1.85 2.1V22zm.925-13l-.6-4H5v4zm5.788 9.713Q13 18.425 13 18t-.288-.712T12 17t-.712.288T11 18t.288.713T12 19t.713-.288M9.7 14h4.6l1.35-9h-7.3zM8 20h8v-2l-1.775-2h-4.45L8 18zm4-2");
}

</style>
