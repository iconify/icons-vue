<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjxrvkz7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-rename-outline-outline-sharp" /></template>
<style>
.hjxrvkz7n {
  fill: currentColor;
  d: path("m10 21l4-4h8v4Zm-6-2h1.4l8.625-8.625l-1.4-1.4L4 17.6ZM18.3 8.925l-4.25-4.2L16.875 1.9L21.1 6.125ZM2 21v-4.25l10.6-10.6l4.25 4.25L6.25 21ZM13.325 9.675l-.7-.7l1.4 1.4Z");
}

</style>
