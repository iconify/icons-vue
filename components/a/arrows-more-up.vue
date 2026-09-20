<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkuxsmbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-more-up" /></template>
<style>
.mkuxsmbtn {
  fill: currentColor;
  d: path("M13 18V9H4V8h10v10zm4-3.98v-9H8v-1h10v10z");
}

</style>
