<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es-77pbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-improvement-and-tools-rounded" /></template>
<style>
.es-77pbkp {
  fill: currentColor;
  d: path("M8.97 3h6.06q.318 0 .459.278q.14.278-.037.547L14 5.892V10.5h-4V5.892L8.548 3.825q-.177-.27-.036-.547Q8.652 3 8.969 3M10 11.5h4v3h-4zm0 4h4v2.406q0 .323-.13.628q-.132.305-.349.522l-.956.955q-.13.131-.267.184t-.298.053t-.298-.053t-.268-.184l-.955-.955q-.218-.218-.348-.522q-.131-.305-.131-.628z");
}

</style>
