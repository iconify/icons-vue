<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tpo-93bpo"/><path class="of_frvb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:default-folder-opened" /></template>
<style>
.of_frvb8m {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.tpo-93bpo {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1.1-2.1h7.1Z");
}

</style>
