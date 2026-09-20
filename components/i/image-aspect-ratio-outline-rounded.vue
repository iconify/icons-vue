<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy7anuq8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-aspect-ratio-outline-rounded" /></template>
<style>
.gy7anuq8p {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6zm3.578-6.23q.23-.23.23-.578t-.23-.577t-.578-.23t-.578.23t-.23.577q0 .349.23.578q.23.23.578.23t.578-.23m3.808 0q.23-.23.23-.578t-.23-.577t-.578-.23t-.578.23t-.23.577q0 .349.23.578t.578.23t.578-.23m3.807 0q.23-.23.23-.578t-.23-.577t-.577-.23t-.578.23t-.23.577q0 .349.23.578t.578.23t.577-.23m0 3.808q.23-.23.23-.578t-.23-.578t-.577-.23t-.578.23t-.23.578t.23.578t.578.23t.577-.23");
}

</style>
