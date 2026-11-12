<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etu4y9b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-search-corner-fill-round" /></template>
<style>
.etu4y9b-v {
  fill: currentColor;
  d: path("M17 11H8.029c.066 1.152.245 2.378.655 3.457c.169.443.382.899.718 1.242c.159.162.363.301.598.301a1 1 0 0 1 0 2a8 8 0 1 1 3.064-15.39A7.99 7.99 0 0 1 18 10a1 1 0 0 1-1 1m-5.029-2c-.066-1.152-.245-2.378-.655-3.457c-.169-.443-.382-.899-.718-1.242c-.911-.929-1.636.515-1.914 1.242c-.41 1.079-.589 2.305-.655 3.457ZM6.026 9c.07-1.363.279-2.778.75-4.062A6 6 0 0 0 4.082 9Zm7.948 0h1.944a6.03 6.03 0 0 0-2.694-4.062c.47 1.283.68 2.699.75 4.062m-7.948 2H4.082a6 6 0 0 0 2.688 4.059l.006.003c-.47-1.283-.68-2.699-.75-4.062m13.295 6.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-1.626-1.218a1.83 1.83 0 1 0-3.39-1.376a1.83 1.83 0 0 0 3.39 1.376");
}

</style>
