<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lura-xb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-sync-24-regular" /></template>
<style>
.lura-xb6j {
  fill: currentColor;
  d: path("M18.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-7.251-9a.75.75 0 0 1 0 1.5H8.116a.75.75 0 0 0-.65.376l-3.898 6.77a.75.75 0 0 0-.007.733l3.614 6.627a.949.949 0 0 0 1.736-.167l4.492-14.12a2.47 2.47 0 0 1 4.492-.483l3.823 6.641c.206.358.305.758.299 1.157a6.5 6.5 0 0 0-1.832-.812l-3.59-6.237a.969.969 0 0 0-1.762.19L10.34 19.294a2.449 2.449 0 0 1-4.482.43l-3.615-6.626a2.25 2.25 0 0 1 .026-2.2l3.897-6.771A2.25 2.25 0 0 1 8.116 3zM15.5 18a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-.55A3.5 3.5 0 0 0 18.5 21a3.5 3.5 0 0 0 2.676-1.243a.5.5 0 0 0-.765-.646A2.5 2.5 0 0 1 18.5 20a2.5 2.5 0 0 1-2-1h1a.5.5 0 0 0 0-1zm6-4a.5.5 0 0 0-.5.5v.55a3.497 3.497 0 0 0-5.337.398a.5.5 0 0 0 .81.588A2.5 2.5 0 0 1 18.5 15c.817 0 1.543.392 2 1h-1a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5");
}

</style>
