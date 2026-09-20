<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b35ucnrih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brand-awareness-outline" /></template>
<style>
.b35ucnrih {
  fill: currentColor;
  d: path("M16 13v-2h4v2zm1.2 7L14 17.6l1.2-1.6l3.2 2.4zm-2-12L14 6.4L17.2 4l1.2 1.6zM3 15V9h4l5-5v16l-5-5zm7-6.15L7.85 11H5v2h2.85L10 15.15zM7.5 12");
}

</style>
