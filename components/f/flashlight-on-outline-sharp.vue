<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw1xmrmda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flashlight-on-outline-sharp" /></template>
<style>
.hw1xmrmda {
  fill: currentColor;
  d: path("M9 21V10.692l-2-3V3h10v4.692l-2 3V21zm2.293-6.293Q11 14.413 11 14t.293-.707T12 13t.707.293T13 14t-.293.707T12 15t-.707-.293M8 5.5h8V4H8zm8 1H8v.9l2 3V20h4v-9.6l2-3zM12 12");
}

</style>
