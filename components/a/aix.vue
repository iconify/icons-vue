<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":207};
const content = `<defs><linearGradient id="SVG2t7eJcWR" x1="5.807%" x2="274.587%" y1="101.291%" y2="-4.88%"><stop offset="0%" class="q8k41n78u"/><stop offset="30.49%" class="q8k41n78u"/><stop offset="92.79%" class="wuk3rabjb"/><stop offset="100%" class="wuk3rabjb"/></linearGradient><linearGradient id="SVGYqkEElXh" x1="-9.904%" x2="128.371%" y1="101.291%" y2="-4.857%"><stop offset="0%" class="q8k41n78u"/><stop offset="30.49%" class="q8k41n78u"/><stop offset="92.79%" class="wuk3rabjb"/><stop offset="100%" class="wuk3rabjb"/></linearGradient><linearGradient id="SVGzTaaJbKn" x1="-136.658%" x2="130.35%" y1="101.291%" y2="-4.857%"><stop offset="0%" class="q8k41n78u"/><stop offset="30.49%" class="q8k41n78u"/><stop offset="92.79%" class="wuk3rabjb"/><stop offset="100%" class="wuk3rabjb"/></linearGradient></defs><path fill="url(#SVG2t7eJcWR)" class="gpql5_gcm"/><path fill="url(#SVGYqkEElXh)" class="ba9fz5bhz"/><path fill="url(#SVGzTaaJbKn)" class="arpftov-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aix" /></template>
<style>
.arpftov-p {
  d: path("M512 206.178h-51.382l-44.086-75.913h-.876l-42.912 75.913h-47.875l65.393-106.63L328.078 0h51.664l39.703 69.703h.876L460.603 0h47.875l-62.763 100.435z");
}

.ba9fz5bhz {
  d: path("M208.731 206.178v-35.739h26.27v-134.7h-26.27V0h96.909v35.739h-26.27v134.7h26.27v35.739z");
}

.gpql5_gcm {
  d: path("m142.163 206.178l-14.595-49.03H59.544l-14.596 49.03H0L67.147.045h54.874l66.27 206.133zM93.991 40.79h-1.46l-22.48 78.274h46.7z");
}

.q8k41n78u {
  stop-color: var(--svg-color--6fdc8c, #6fdc8c);
}

.wuk3rabjb {
  stop-color: var(--svg-color--009d9a, #009d9a);
}

</style>
