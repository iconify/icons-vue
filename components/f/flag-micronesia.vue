<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="unl2apbha"/><path class="he7m_0bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-micronesia" /></template>
<style>
.he7m_0bad {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.3 7.6l-.584 1.797h-1.889l1.528 1.11l-.583 1.796l1.528-1.11l1.528 1.11l-.583-1.796l1.528-1.11h-1.889zm8.603 9.816v-1.889l-1.11 1.528l-1.796-.583L25.107 18l-1.11 1.528l1.796-.583l1.11 1.528v-1.889L28.7 18zm-7.658 8.077l.583-1.796l-1.528 1.11l-1.528-1.11l.583 1.796l-1.528 1.11h1.889L18.3 28.4l.584-1.797h1.889zm-8.438-8.438l-1.11-1.528v1.889L7.9 18l1.797.584v1.889l1.11-1.528l1.796.583L11.493 18l1.11-1.528z");
}

.unl2apbha {
  fill: var(--svg-color--75b2dd, #75b2dd);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

</style>
