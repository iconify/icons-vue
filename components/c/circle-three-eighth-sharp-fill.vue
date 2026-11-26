<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-lk5g9qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-eighth-sharp-fill" /></template>
<style>
.u-lk5g9qr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM12 12L16.9497 16.9497C18.2625 15.637 19 13.8565 19 12C19 8.134 15.866 5 12 5Z");
}

</style>
