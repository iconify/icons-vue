<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgdmt1bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:end-mill" /></template>
<style>
.rgdmt1bki {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 1.75h-1.5q-2.5 0-2.5 2.5v4.5q0 .72.207 1.232q-.1.105-.153.239q-.054.134-.054.279V19q0 .149.057.287t.163.243l2.5 2.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.5-2.5q.106-.105.163-.243T15.25 19v-8.5q0-.084-.019-.166q-.018-.082-.055-.158q-.036-.076-.088-.142q-.053-.066-.118-.119q.28-.524.28-1.165v-4.5q0-1.036-.732-1.768T12.75 1.75m1 13.242l-3.5 1.4v-1.884l3.5-1.4zm-3.5 3.016l3.5-1.4v2.081L12 20.439l-1.75-1.75zm0-5.116v-1.769q.436.127 1 .127h1.5q.541 0 1-.2v.442z");
}

</style>
