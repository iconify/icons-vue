<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hob-y5b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-chevron-down-20-filled" /></template>
<style>
.hob-y5b-j {
  fill: currentColor;
  d: path("M3.552 2.443c.854-.478 1.943-.59 2.985-.326a1.93 1.93 0 0 1 1.199.91l.898 1.566a2.5 2.5 0 0 1-.829 3.354l-.79.502c-.327.207-.447.524-.372.775c.267.897.86 1.894 1.513 2.576c.194.203.55.252.898.05l.437-.256a2.5 2.5 0 0 1 3.441.938l.804 1.435a1.84 1.84 0 0 1 .12 1.536c-.371 1.003-1.086 1.811-1.965 2.216c-.893.412-1.939.396-2.885-.235c-1.497-.999-3.302-2.68-4.937-5.482c-1.656-2.838-2.074-5.256-2.027-7.057c.03-1.154.641-2.016 1.51-2.502m13.595 1.704a.5.5 0 1 1 .707.707l-3 3a.5.5 0 0 1-.707 0l-3-3a.5.5 0 1 1 .707-.707L14.5 6.793z");
}

</style>
