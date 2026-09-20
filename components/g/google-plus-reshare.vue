<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3lm1ublv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:google-plus-reshare" /></template>
<style>
.u3lm1ublv {
  fill: currentColor;
  d: path("m16 17l-1.425-1.4l4.6-4.6l-4.6-4.6L16 5l6 6zM2 19v-4q0-2.075 1.463-3.537T7 10h6.175l-3.6-3.6L11 5l6 6l-6 6l-1.425-1.4l3.6-3.6H7q-1.25 0-2.125.875T4 15v4z");
}

</style>
