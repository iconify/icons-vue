<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vbxe0xtoi"/><path class="gkx4eacaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-austria" /></template>
<style>
.gkx4eacaa {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4M4 31h28a4 4 0 0 0 4-4v-4H0v4a4 4 0 0 0 4 4");
}

.vbxe0xtoi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13h36v10H0z");
}

</style>
