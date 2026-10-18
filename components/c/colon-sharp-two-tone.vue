<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4najrbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:colon-sharp-two-tone" /></template>
<style>
.f4najrbyk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 8C14 9.1046 13.1046 10 12 10C10.8954 10 10 9.1046 10 8C10 6.8954 10.8954 6 12 6C13.1046 6 14 6.8954 14 8ZM14 16C14 17.1046 13.1046 18 12 18C10.8954 18 10 17.1046 10 16C10 14.8954 10.8954 14 12 14C13.1046 14 14 14.8954 14 16Z");
}

</style>
