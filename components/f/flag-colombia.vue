<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rj-y8llhr"/><path class="y51vjfbzm"/><path class="z2w88ujgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-colombia" /></template>
<style>
.rj-y8llhr {
  fill: var(--svg-color--fbd116, #fbd116);
  d: path("M32 5H4a4 4 0 0 0-4 4v9h36V9a4 4 0 0 0-4-4");
}

.y51vjfbzm {
  fill: var(--svg-color--22408c, #22408c);
  d: path("M0 18h36v7H0z");
}

.z2w88ujgm {
  fill: var(--svg-color--ce2028, #ce2028);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2H0z");
}

</style>
