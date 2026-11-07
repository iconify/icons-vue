<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="suepciomu"/><path class="yubiy201s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.suepciomu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.476 4.234l-.746-.747l4.827-2.384c.279-.137.607-.137.886 0l9 4.445a1 1 0 0 1 .557.896v11.112a1 1 0 0 1-.401.8Zm-1.893.935l14.135 14.135l-7.275 3.593a1 1 0 0 1-.886 0l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l2.279-1.126Z");
}

.yubiy201s {
  d: path("m2.707 2.293l5.821 5.821l.017.016l13.162 13.163a.999.999 0 1 1-1.414 1.414L13 15.414V22a1 1 0 0 1-.556.896l-.001.001a1.01 1.01 0 0 1-.886 0l-.001-.001A1 1 0 0 1 11 22v-8.586L7.238 9.653L2.557 7.341a1 1 0 0 1 0-1.793l.008-.004a1 1 0 0 1 .466-.099L1.293 3.707a.999.999 0 1 1 1.414-1.414m18.736 3.255a1 1 0 0 1 0 1.793l-6.627 3.272a1 1 0 0 1-.885-1.793l6.626-3.272a1 1 0 0 1 .878-.004Z");
}

</style>
