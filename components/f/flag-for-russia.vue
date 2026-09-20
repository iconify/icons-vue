<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="s20544kmx"/><path class="rviwuksrz"/><path class="j37us9hup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-russia" /></template>
<style>
.j37us9hup {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.rviwuksrz {
  fill: var(--svg-color--22408c, #22408c);
  d: path("M0 13h36v10H0z");
}

.s20544kmx {
  fill: var(--svg-color--ce2028, #ce2028);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-4h36z");
}

</style>
