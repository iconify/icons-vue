<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fr-0a1bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-edit-32-regular" /></template>
<style>
.fr-0a1bug {
  fill: currentColor;
  d: path("M2 8.5A4.5 4.5 0 0 1 6.5 4h19A4.5 4.5 0 0 1 30 8.5v6.42a4.4 4.4 0 0 0-2-.42v-2.826l-11.526 6.207a1 1 0 0 1-.948 0L4 11.674V21.5A2.5 2.5 0 0 0 6.5 24h10.375l-.43.433c-.44.444-.773.98-.976 1.567H6.5A4.5 4.5 0 0 1 2 21.5zm14 7.364l12-6.461V8.5A2.5 2.5 0 0 0 25.5 6h-19A2.5 2.5 0 0 0 4 8.5v.903zm14.144 5.06l-8.61 8.543a2.8 2.8 0 0 1-1.269.721l-3.02.778a1 1 0 0 1-1.216-1.22l.79-3.05a2.66 2.66 0 0 1 .686-1.206l8.567-8.64a2.88 2.88 0 0 1 4.144.057a2.88 2.88 0 0 1-.072 4.017");
}

</style>
