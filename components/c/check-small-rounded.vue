<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt98knbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-small-rounded" /></template>
<style>
.wt98knbjr {
  fill: currentColor;
  d: path("m10 14.312l6.246-6.266q.14-.14.354-.14t.354.14t.14.354t-.14.354l-6.389 6.369q-.242.243-.565.243t-.565-.243l-2.389-2.37q-.14-.14-.14-.353t.14-.354t.354-.14t.354.14z");
}

</style>
