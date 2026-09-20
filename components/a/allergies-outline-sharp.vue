<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyhix5drb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:allergies-outline-sharp" /></template>
<style>
.qyhix5drb {
  fill: currentColor;
  d: path("M9.5 18h2v-7.25l-2.1-4.2l-1.8.9l1.9 3.8zm3 0h2v-6.75l1.9-3.8l-1.8-.9l-2.1 4.2zm4.4-4.55l2-4l-1.8-.9l-2 4zm-9.8 0l1.8-.9l-2-4l-1.8.9zM12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m0-2q3.35 0 5.675-2.325T20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20m0-8");
}

</style>
