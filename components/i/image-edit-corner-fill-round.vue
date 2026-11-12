<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrrwng0va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-fill-round" /></template>
<style>
.lrrwng0va {
  fill: currentColor;
  d: path("M15 12c-.927 0-1.8.424-2.368 1.157l-.938-.877a3.825 3.825 0 0 0-5.401.013L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1Zm.779-2.158a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684M13 21v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1m-1.957-6.591l.735.687a1 1 0 0 0 .222.157V21a1 1 0 0 1-1 1H7a4.99 4.99 0 0 1-4.584-3.001l5.291-5.292a1.83 1.83 0 0 1 1.982-.402c.259.105.434.244.628.425Z");
}

</style>
