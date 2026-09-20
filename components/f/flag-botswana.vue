<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vbxe0xtoi"/><path class="ld6tu2-ny"/><path class="n8dcwacql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-botswana" /></template>
<style>
.ld6tu2-ny {
  fill: var(--svg-color--75aadb, #75aadb);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H0z");
}

.n8dcwacql {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 16h36v4H0z");
}

.vbxe0xtoi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13h36v10H0z");
}

</style>
