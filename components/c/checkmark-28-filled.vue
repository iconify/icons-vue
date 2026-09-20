<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="cn0o6_bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-28-filled" /></template>
<style>
.cn0o6_bpj {
  fill: currentColor;
  d: path("m10.5 19.586l-6.293-6.293a1 1 0 0 0-1.414 1.414l7 7a1 1 0 0 0 1.414 0l14-14a1 1 0 0 0-1.414-1.414z");
}

</style>
