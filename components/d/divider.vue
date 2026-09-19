<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="b4ve1kb5k"/><path class="ds0sjvb6n"/></g><g class="y9tr6bcfx"><path class="tfnh6wbjp"/><path class="ij5mdo90n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:divider" /></template>
<style>
.b4ve1kb5k {
  d: path("M8.095 5.5h31.81a2.27 2.27 0 0 1 2.276 2.277v13.946A2.27 2.27 0 0 1 39.905 24H8.095a2.27 2.27 0 0 1-2.276-2.277V7.777A2.27 2.27 0 0 1 8.095 5.5");
}

.ds0sjvb6n {
  d: path("M10.515 7.875h11.019c.757 0 1.366.609 1.366 1.366v11.018c0 .757-.61 1.366-1.366 1.366H10.515a1.363 1.363 0 0 1-1.366-1.366V9.241c0-.757.61-1.366 1.366-1.366m15.933 0h11.055c.747 0 1.348.6 1.348 1.346v3.305c0 .745-.601 1.346-1.348 1.346H26.448c-.747 0-1.348-.6-1.348-1.346V9.22c0-.746.601-1.346 1.348-1.346m0 7.848h11.055c.747 0 1.348.6 1.348 1.346v3.211c0 .746-.601 1.346-1.348 1.346H26.448c-.747 0-1.348-.6-1.348-1.346v-3.211c0-.746.601-1.346 1.348-1.346");
}

.ij5mdo90n {
  d: path("M16.209 27.714h4.757v4.554H16.21zm10.825 0h4.757v4.554h-4.757zm-10.825 6.519h4.757v4.553H16.21zm10.825 0h4.757v4.553h-4.757z");
}

.tfnh6wbjp {
  d: path("M8.095 24h31.81a2.27 2.27 0 0 1 2.276 2.277v13.946a2.27 2.27 0 0 1-2.276 2.277H8.095a2.27 2.27 0 0 1-2.276-2.277V26.277A2.27 2.27 0 0 1 8.095 24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
