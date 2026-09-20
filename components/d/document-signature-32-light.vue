<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-rz0oblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-signature-32-light" /></template>
<style>
.s-rz0oblf {
  fill: currentColor;
  d: path("M6 5a2 2 0 0 1 2-2h8v7a3 3 0 0 0 3 3h3.316l.991-1H19a2 2 0 0 1-2-2V3.073a2 2 0 0 1 .879.513l7.193 7.193c.371-.14.757-.227 1.146-.263l-.097-.102l-7.535-7.535A3 3 0 0 0 16.465 2H8a3 3 0 0 0-3 3v22a3 3 0 0 0 3 3h16a3 3 0 0 0 3-3v-6.327l-1 .992V27a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2zm22.644 11.924l-8.61 8.543a2.8 2.8 0 0 1-1.269.721l-3.02.778a1 1 0 0 1-.245.032V27h-7a.5.5 0 0 1 0-1h5.996q0-.125.033-.253l.79-3.052c.118-.455.355-.871.686-1.205l8.567-8.64a2.88 2.88 0 0 1 4.144.057a2.88 2.88 0 0 1-.072 4.017");
}

</style>
