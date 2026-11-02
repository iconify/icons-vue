<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k08e5fw7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-fill" /></template>
<style>
.k08e5fw7e {
  fill: currentColor;
  d: path("M3.293 16.293L11 8.586V8c0-1.232-.873-2.459-1.707-3.293l-1-1A1 1 0 0 1 9 2h4c1.804 0 3.47 1.056 4.707 2.293l1 1C19.422 6.008 20 6.961 20 8c0 .468.395.98.707 1.293l1 1a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-1-1c-.269-.268-.584-.513-.945-.641l-7.641 7.641a3.121 3.121 0 1 1-4.414-4.414");
}

</style>
