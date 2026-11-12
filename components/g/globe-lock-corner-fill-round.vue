<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkmwedblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-lock-corner-fill-round" /></template>
<style>
.wkmwedblz {
  fill: currentColor;
  d: path("M17 11H8.029c.066 1.152.245 2.378.655 3.457c.169.443.382.899.718 1.242c.159.162.363.301.598.301a1 1 0 0 1 0 2a8 8 0 1 1 3.064-15.39A7.99 7.99 0 0 1 18 10a1 1 0 0 1-1 1m-5.029-2c-.066-1.152-.245-2.378-.655-3.457c-.169-.443-.382-.899-.718-1.242c-.911-.929-1.636.515-1.914 1.242c-.41 1.079-.589 2.305-.655 3.457ZM6.026 9c.07-1.363.279-2.778.75-4.062A6 6 0 0 0 4.082 9Zm7.948 0h1.944a6.03 6.03 0 0 0-2.694-4.062c.47 1.283.68 2.699.75 4.062m-7.948 2H4.082a6 6 0 0 0 2.688 4.059l.006.003c-.47-1.283-.68-2.699-.75-4.062M22 18v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829V15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18m-4-3a1 1 0 0 0-2 0Zm-3 2a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1Z");
}

</style>
