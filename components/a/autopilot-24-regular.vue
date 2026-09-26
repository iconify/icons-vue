<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1r61bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autopilot-24-regular" /></template>
<style>
.bg1r61bbz {
  fill: currentColor;
  d: path("M19.242 3c3.49 0 5.087 4.35 2.427 6.608l-8.703 7.39q-.055.053-.111.104l-1.534 1.327a.7.7 0 0 1-.16.102l-3.305 2.807a2.68 2.68 0 0 1-4.051-3.389l4.17-7.181l-4.642-2.73A2.706 2.706 0 0 1 4.705 3zM5.102 18.703a1.18 1.18 0 0 0 1.784 1.491l5.048-4.288a1.747 1.747 0 0 0-.24-2.72l-2.447-1.623zM10.682 4.5c.836 1.12 1.051 2.692.272 4.083l-.945 1.687l2.514 1.665a3.23 3.23 0 0 1 1.421 2.264l6.754-5.734c1.596-1.356.638-3.965-1.456-3.965zm-5.977 0a1.207 1.207 0 0 0-.611 2.245l4.641 2.73l.91-1.625c.814-1.453-.178-3.235-1.803-3.345l-.16-.005z");
}

</style>
