<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgbr1b71u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:donut-large-outline-sharp" /></template>
<style>
.hgbr1b71u {
  fill: currentColor;
  d: path("M11.025 21.95q-3.85-.375-6.425-3.225T2.025 12T4.6 5.275t6.425-3.225v3q-2.6.35-4.3 2.325T5.025 12t1.7 4.625t4.3 2.325zm2 0v-3q2.35-.3 3.975-1.95t1.975-4h3q-.35 3.575-2.863 6.088t-6.087 2.862M18.975 11Q18.625 8.65 17 7t-3.975-1.95v-3q3.575.35 6.088 2.863T21.975 11z");
}

</style>
