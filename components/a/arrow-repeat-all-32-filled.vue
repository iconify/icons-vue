<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fc737v-uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-repeat-all-32-filled" /></template>
<style>
.fc737v-uc {
  fill: currentColor;
  d: path("M26.437 10.46c.484-.483 1.276-.49 1.695.052A9 9 0 0 1 21 25h-8.732l2.866 2.866a1.25 1.25 0 1 1-1.768 1.768l-5-5a1.25 1.25 0 0 1 0-1.768l5-5a1.25 1.25 0 0 1 1.768 1.768L12.268 22.5H21a6.5 6.5 0 0 0 5.355-10.183c-.394-.572-.41-1.365.081-1.856m-9.57-8.094a1.25 1.25 0 0 1 1.767 0l5 5a1.25 1.25 0 0 1 0 1.768l-5 5a1.25 1.25 0 0 1-1.768-1.768L19.732 9.5H11a6.5 6.5 0 0 0-5.356 10.182c.394.571.41 1.364-.08 1.855c-.485.485-1.278.493-1.697-.05A9 9 0 0 1 11 7h8.732l-2.866-2.866a1.25 1.25 0 0 1 0-1.768");
}

</style>
