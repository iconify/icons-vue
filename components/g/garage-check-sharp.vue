<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5mg3-bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-check-sharp" /></template>
<style>
.m5mg3-bzs {
  fill: currentColor;
  d: path("m7.304 10.5l1.046-3h7.3l1.046 3zm1.85 3.04q.23-.23.23-.54t-.23-.54t-.538-.23t-.54.23t-.23.54t.23.54t.54.23t.539-.23m7.453 6.076l3.357-3.358l-.557-.558l-2.8 2.8l-1.4-1.4l-.558.558zm3.535-4.855q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836t1.164-2.835t2.836-1.165q1.67 0 2.835 1.165M11.91 21H3V3h18v9.39q-.65-.474-1.403-.765q-.753-.29-1.597-.377L16.344 6.5H7.656L6 11.254V17.5h1v-2h4.29q-.17.485-.269 1.014q-.098.528-.098 1.082q0 .933.26 1.792q.261.858.727 1.612");
}

</style>
