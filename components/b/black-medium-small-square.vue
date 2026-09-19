<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fb3_dhlcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-medium-small-square" /></template>
<style>
.fb3_dhlcc {
  fill: currentColor;
  d: path("M12 12h40v40H12z");
}

</style>
