<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="de0aidizb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-puppet" /></template>
<style>
.de0aidizb {
  fill: var(--svg-color--ffae1a, #ffae1a);
  d: path("M25.089 11.822H18.7l-3.433-3.434V2H6.911v8.357H13.3l3.422 3.422v4.431l-3.434 3.434H6.911V30h8.357v-6.388l3.432-3.434h6.388ZM9.7 4.786h2.786v2.785H9.7ZM12.482 27.2H9.7v-2.783h2.786Z");
}

</style>
