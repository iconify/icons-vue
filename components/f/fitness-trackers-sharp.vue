<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unp-8ub0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fitness-trackers-sharp" /></template>
<style>
.unp-8ub0g {
  fill: currentColor;
  d: path("m4.846 21l-.9-3.02H3V6.02h.966L4.846 3h4.308l.862 3.02H11v11.96h-.985L9.154 21zM4 16.98h6V7.02H4zM14.75 21V8.73h-.692V6.77h.692V3H21v3.77h.692v1.96H21V21zm1-12.75V20H20V8.25zm0-1H20V4h-4.25z");
}

</style>
