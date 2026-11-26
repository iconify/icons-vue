<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mrr4tifxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-seven-eighth-sharp-fill" /></template>
<style>
.mrr4tifxu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM12 12L7.0503 7.0503C5.7375 8.363 5 10.1435 5 12C5 15.866 8.134 19 12 19C15.866 19 19 15.866 19 12C19 8.134 15.866 5 12 5Z");
}

</style>
