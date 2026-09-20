<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1li87bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-16-regular" /></template>
<style>
.g1li87bgt {
  fill: currentColor;
  d: path("M7.146.646a.5.5 0 0 1 .708 0l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 1 1-.708-.708l.643-.642a5 5 0 0 0-2.937 8.88a.5.5 0 1 1-.63.777A6 6 0 0 1 7.797 2.003l-.65-.65a.5.5 0 0 1 0-.707m3.929 2.766a.5.5 0 0 1 .703-.073a6 6 0 0 1-3.575 10.658l.65.65a.5.5 0 0 1-.707.707l-1.5-1.5a.5.5 0 0 1 0-.708l1.5-1.5a.5.5 0 0 1 .708.708l-.643.642a5 5 0 0 0 2.937-8.88a.5.5 0 0 1-.073-.704");
}

</style>
