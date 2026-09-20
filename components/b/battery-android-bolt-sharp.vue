<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vem53_6eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-bolt-sharp" /></template>
<style>
.vem53_6eh {
  fill: currentColor;
  d: path("M2 17V7h15.723l-6.277 7.846h4.785L15.796 17zm15.867-.77l.604-3.384h-2.855l4.069-5.077h.448l-.604 3.385h2.856l-4.07 5.077z");
}

</style>
