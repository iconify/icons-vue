<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3thqqujr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bolt-sharp" /></template>
<style>
.k3thqqujr {
  fill: currentColor;
  d: path("m9.154 20.885l1-6.885h-4.25l7.48-10.788h.462L12.866 11h5l-8.25 9.885z");
}

</style>
