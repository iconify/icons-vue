<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rjuvlybel"/><path class="ssu-a5g-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:computer-mouse" /></template>
<style>
.rjuvlybel {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M20 2.047V2a2 2 0 0 0-4 0v.047C7.737 2.422 6 5.127 6 7v17c0 6.627 5.373 12 12 12s12-5.373 12-12V7c0-1.873-1.737-4.578-10-4.953");
}

.ssu-a5g-o {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M22 9.199v-7a36 36 0 0 0-2-.151V9a2 2 0 0 1-4 0V2.048q-1.067.051-2 .151v7C7.459 9.89 6 12.29 6 14v2c0-1.725 1.482-4.153 8.169-4.819C14.646 12.228 16.171 13 18 13s3.355-.772 3.831-1.819C28.518 11.847 30 14.275 30 16v-2c0-1.71-1.459-4.11-8-4.801");
}

</style>
