<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z636gybwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:headset-mic-sharp" /></template>
<style>
.z636gybwm {
  fill: currentColor;
  d: path("M12 23v-2h7v-1h-4v-8h4v-1q0-2.9-2.05-4.95T12 4T7.05 6.05T5 11v1h4v8H3v-9q0-1.85.713-3.488T5.65 4.65t2.863-1.937T12 2t3.488.713T18.35 4.65t1.938 2.863T21 11v12z");
}

</style>
