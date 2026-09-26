<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp-npkaht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:autopilot-24-filled" /></template>
<style>
.jp-npkaht {
  fill: currentColor;
  d: path("M19.242 3c3.49 0 5.087 4.35 2.427 6.608l-8.703 7.39q-.055.053-.111.104l-1.534 1.327a.7.7 0 0 1-.16.102l-3.305 2.807a2.68 2.68 0 0 1-4.051-3.389l4.17-7.181l-4.642-2.73A2.706 2.706 0 0 1 4.705 3zM5.102 18.703a1.18 1.18 0 0 0 1.784 1.491l5.048-4.288a1.747 1.747 0 0 0-.24-2.72l-2.447-1.623zM4.705 4.5a1.207 1.207 0 0 0-.611 2.245l4.641 2.73l.91-1.625c.814-1.453-.178-3.235-1.803-3.345l-.16-.005z");
}

</style>
