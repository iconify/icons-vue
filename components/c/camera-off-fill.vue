<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1q4dfb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-fill" /></template>
<style>
.o1q4dfb7q {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414L18.586 21H5a3 3 0 0 1-3-3V9c0-1.204.717-2.291 1.825-2.761L1.293 3.707a.999.999 0 1 1 1.414-1.414M21.923 18.68L7.914 4.672l.379-.379C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6H19a3 3 0 0 1 3 3v9q0 .345-.077.68m-7.98-2.322l-1.46-1.461A1.2 1.2 0 0 1 12 15a2 2 0 0 1-2-2c0-.166.037-.33.103-.483l-1.461-1.46C8.243 11.627 8 12.299 8 13a4 4 0 0 0 4 4c.701 0 1.373-.243 1.943-.642");
}

</style>
