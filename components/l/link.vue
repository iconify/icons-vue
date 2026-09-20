<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wb4rq6bpb"/><path class="kgh-7rw1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:link" /></template>
<style>
.kgh-7rw1f {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("m20.845 27l-6 6s-6 6-12 0s0-12 0-12l8-8s6-6 12 0c1.125 1.125 1.822 2.62 1.822 2.62l-3.354 3.349s.135-1.365-1.469-2.969c0 0-3-3-6 0l-8 8s-3 3 0 6s6 0 6 0l3.729-3.729s1.854 1.521 5.646.354z");
}

.wb4rq6bpb {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("m15 9l6-6s6-6 12 0s0 12 0 12l-8 8s-6 6-12 0c-1.125-1.125-1.822-2.62-1.822-2.62l3.353-3.348S14.396 18.396 16 20c0 0 3 3 6 0l8-8s3-3 0-6s-6 0-6 0l-3.729 3.729s-1.854-1.521-5.646-.354z");
}

</style>
