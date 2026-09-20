<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdt9nilrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-24-regular" /></template>
<style>
.wdt9nilrk {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zM6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v5h6.75V4.5zm5 8.25H4.5v5c0 .966.784 1.75 1.75 1.75h5zm1.5 0v6.75h5a1.75 1.75 0 0 0 1.75-1.75v-5zm6.75-1.5v-5a1.75 1.75 0 0 0-1.75-1.75h-5v6.75z");
}

</style>
