<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="axfluubhb"/><path class="ywz27nq4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:disappointed-face" /></template>
<style>
.axfluubhb {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 9.64C1.69 9.64.21 79.5.21 93.33S28.77 118.36 64 118.36c35.24 0 63.79-11.21 63.79-25.03c0-13.83-1.47-83.69-63.79-83.69");
}

.ywz27nq4m {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M38.31 97.58c-.69 0-1.38-.24-1.95-.72a2.997 2.997 0 0 1-.33-4.23c7-8.19 17.19-12.89 27.97-12.89c10.77 0 20.97 4.7 27.96 12.89c1.08 1.26.93 3.15-.33 4.23a2.997 2.997 0 0 1-4.23-.33A30.73 30.73 0 0 0 64 85.75c-9.02 0-17.55 3.93-23.4 10.79c-.6.69-1.44 1.04-2.29 1.04m-4.3-37.35c.03-.94.18-1.84.4-2.71c1.74-.23 3.62-.59 5.68-1.21c3.04-.91 5.3-2.41 7.05-4.04c1.93 1.83 3.17 4.72 3.09 7.99c-.12 5.53-3.85 9.99-8.34 9.97c-4.47.01-7.99-4.48-7.88-10m60.4 0c-.03-.94-.18-1.84-.4-2.71c-1.74-.23-3.62-.59-5.68-1.21c-3.04-.91-5.3-2.41-7.05-4.04c-1.93 1.83-3.17 4.72-3.09 7.99c.12 5.53 3.85 9.99 8.34 9.97c4.46.01 7.99-4.48 7.88-10");
}

</style>
