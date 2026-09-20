<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfj_hbcxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-one-sharp" /></template>
<style>
.sfj_hbcxi {
  fill: currentColor;
  d: path("M12 17h2V7h-4v2h2zm9 4H3V3h18z");
}

</style>
