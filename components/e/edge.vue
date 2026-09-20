<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8c8s9noy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:edge" /></template>
<style>
.h8c8s9noy {
  fill: var(--svg-color--0ecc5f, #0ecc5f);
  d: path("M20.999 12a8 8 0 0 0-.011-.429q-.009-.147-.021-.294q-.002-.056-.009-.114a9 9 0 0 0-.044-.374v-.02a9 9 0 1 0-1.88 6.844l-2.76-1.967c-1.135 1.325-2.653 1.979-4.27 1.979A5.606 5.606 0 0 1 6.377 12A5.6 5.6 0 0 1 12 6.376a5.61 5.61 0 0 1 5.367 3.937h-5.362l-1.437 3.375H20.85a10 10 0 0 0 .14-1.347c.006-.09.009-.2.009-.34");
}

</style>
