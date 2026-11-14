<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imtruo43m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grant-dao" /></template>
<style>
.imtruo43m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 4.75q0 1.209.686 2H4.75q-2.5 0-2.5 2.5v.5q0 2.177 1.896 2.458q-.396.761-.396 1.917v3.75q0 3.375 3.375 3.375h9.75q3.375 0 3.375-3.375v-3.75q0-1.174-.409-1.94q.663-.154 1.177-.667q.732-.732.732-1.768v-.5q0-1.036-.732-1.768T19.25 6.75h-2.186q.686-.791.686-2q0-1.099-.882-1.595q-.798-.449-1.862-.083q-1.716.59-3.006 2.78q-1.29-2.19-3.006-2.78q-1.064-.366-1.862.083q-.882.496-.882 1.595");
}

</style>
