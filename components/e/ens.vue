<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGKorqScqs)" class="n23y_belc"/><defs><linearGradient id="SVGKorqScqs" x1="7.289" x2="19.667" y1="4.929" y2="19.59" gradientUnits="userSpaceOnUse"><stop class="s4mwgqfbm"/><stop offset="1" class="od8p9tb1w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ens" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n23y_belc {
  d: path("M6.05 10.28c.18.385.615 1.135.615 1.135L11.715 3L6.79 6.47c-.295.2-.535.465-.7.775a3.63 3.63 0 0 0-.035 3.035zm-1.995 2.77a5.7 5.7 0 0 0 2.2 4.12L11.71 21s-3.405-4.95-6.28-9.885a5 5 0 0 1-.58-1.68a2.7 2.7 0 0 1 0-.805l-.22.425c-.29.6-.49 1.24-.585 1.9c-.06.7-.05 1.4.015 2.1zm13.895.67a20 20 0 0 0-.615-1.135L12.29 21l4.925-3.465c.29-.2.53-.465.7-.78a3.63 3.63 0 0 0 .03-3.035zm1.995-2.77a5.7 5.7 0 0 0-2.2-4.12L12.29 3s3.405 4.95 6.28 9.885a5 5 0 0 1 .575 1.68c.04.265.04.54 0 .805l.22-.425c.295-.6.49-1.24.59-1.9c.06-.7.05-1.4-.015-2.1z");
}

.od8p9tb1w {
  stop-color: var(--svg-color--53b1ef, #53b1ef);
}

.s4mwgqfbm {
  stop-color: var(--svg-color--7c97fa, #7c97fa);
}

</style>
