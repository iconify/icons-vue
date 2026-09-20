<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kntbfwb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-download-48-regular" /></template>
<style>
.kntbfwb5i {
  fill: currentColor;
  d: path("M25.25 6.25a1.25 1.25 0 1 0-2.5 0v26.482l-8.366-8.366a1.25 1.25 0 0 0-1.768 1.768l10.5 10.5a1.25 1.25 0 0 0 1.768 0l10.5-10.5a1.25 1.25 0 0 0-1.768-1.768l-8.366 8.366zm-14 34.25a1.25 1.25 0 1 0 0 2.5h25.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
