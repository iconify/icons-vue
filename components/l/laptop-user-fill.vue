<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plr8i_beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-user-fill" /></template>
<style>
.plr8i_beu {
  fill: currentColor;
  d: path("M4 6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v9.171A3.001 3.001 0 0 1 19 21H5a3 3 0 0 1-1-5.829Zm5 2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 7a1 1 0 0 0 1-1c0-.257-.075-.506-.209-.725C15.124 12.188 13.099 12 12 12s-3.124.188-3.791 1.275A1.4 1.4 0 0 0 8 14a1 1 0 0 0 1 1ZM5 17a1 1 0 0 0 0 2h14a1 1 0 0 0 0-2Z");
}

</style>
