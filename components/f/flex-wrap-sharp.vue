<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otoq3qbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flex-wrap-sharp" /></template>
<style>
.otoq3qbjd {
  fill: currentColor;
  d: path("M1 22v-9h6v9zm8 0v-9h6v9zm8 0v-9h6v9zm-6-2h2v-5h-2zM1 11V2h6v9zm8 0V2h6v9zm8 0V2h6v9zM3 9h2V4H3zm16 0h2V4h-2z");
}

</style>
